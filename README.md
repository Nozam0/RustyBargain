# Descripción del proyecto
Rusty Bargain es un servicio de venta de coches de segunda mano que está desarrollando una app para atraer a nuevos clientes. Gracias a esa app, puedes averiguar rápidamente el valor de mercado de tu coche.

# Objetivo

Generar un modelo de predicción del target "Price", buscando la mejor velocidad y calidad de predicción.

# Descripción de los datos

*Características*
    DateCrawled — fecha en la que se descargó el perfil de la base de datos
    VehicleType — tipo de carrocería del vehículo
    RegistrationYear — año de matriculación del vehículo
    Gearbox — tipo de caja de cambios
    Power — potencia (CV)
    Model — modelo del vehículo
    Mileage — kilometraje (medido en km de acuerdo con las especificidades regionales del conjunto de datos)
    RegistrationMonth — mes de matriculación del vehículo
    FuelType — tipo de combustible
    Brand — marca del vehículo
    NotRepaired — vehículo con o sin reparación
    DateCreated — fecha de creación del perfil
    NumberOfPictures — número de fotos del vehículo
    PostalCode — código postal del propietario del perfil (usuario)
    LastSeen — fecha de la última vez que el usuario estuvo activo

*Target*
    Price — precio (en euros).
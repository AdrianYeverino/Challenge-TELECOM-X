#### Diccionario de datos

- `customerID`: número de identificación único de cada cliente
- `Churn`: si el cliente dejó o no la empresa
- `gender`: género (masculino y femenino)
- `SeniorCitizen`: información sobre si un cliente tiene o no una edad igual o mayor a 65 años
- `Partner`: si el cliente tiene o no una pareja
- `Dependents`: si el cliente tiene o no dependientes
- `tenure`: meses de contrato del cliente
- `PhoneService`: suscripción al servicio telefónico
- `MultipleLines`: suscripción a más de una línea telefónica
- `InternetService`: suscripción a un proveedor de internet
- `OnlineSecurity`: suscripción adicional de seguridad en línea
- `OnlineBackup`: suscripción adicional de respaldo en línea
- `DeviceProtection`: suscripción adicional de protección del dispositivo
- `TechSupport`: suscripción adicional de soporte técnico, menor tiempo de espera
- `StreamingTV`: suscripción de televisión por cable
- `StreamingMovies`: suscripción de streaming de películas
- `Contract`: tipo de contrato
- `PaperlessBilling`: si el cliente prefiere recibir la factura en línea
- `PaymentMethod`: forma de pago
- `Charges.Monthly`: total de todos los servicios del cliente por mes
- `Charges.Total`: total gastado por el cliente

#### Diccionario de datos (versión actualizada en el transcurso del proyecto)

- `Churned`: indica si el cliente canceló el servicio (True/False)  
  *(antes: Churn - Yes/No)*
  
- `Gender`: género del cliente (Female/Male)  
  *(antes: gender)*

- `Is_Senior`: indica si el cliente es adulto mayor (65+ años) (True/False)  
  *(antes: SeniorCitizen - 1/0)*

- `Has_Partner`: indica si el cliente tiene pareja (True/False)  
  *(antes: Partner - Yes/No)*

- `Has_Dependents`: indica si el cliente tiene dependientes (True/False)  
  *(antes: Dependents - Yes/No)*

- `Tenure_Months`: meses de permanencia del cliente  
  *(antes: tenure)*

- `Has_Phone_Service`: indica si tiene servicio telefónico (True/False)  
  *(antes: PhoneService - Yes/No)*

- `Has_Multiple_Lines`: indica si tiene múltiples líneas telefónicas (True/False)  
  *(antes: MultipleLines - Yes/No/No phone service)*

- `Internet_Service_Type`: tipo de servicio de internet (DSL/Fiber optic/No)  
  *(antes: InternetService)*

- `Has_Online_Security`: indica si tiene seguridad en línea (True/False)  
  *(antes: OnlineSecurity - Yes/No/No internet service)*

- `Has_Online_Backup`: indica si tiene respaldo en línea (True/False)  
  *(antes: OnlineBackup - Yes/No/No internet service)*

- `Has_Device_Protection`: indica si tiene protección de dispositivo (True/False)  
  *(antes: DeviceProtection - Yes/No/No internet service)*

- `Has_Tech_Support`: indica si tiene soporte técnico premium (True/False)  
  *(antes: TechSupport - Yes/No/No internet service)*

- `Has_Streaming_TV`: indica si tiene TV por streaming (True/False)  
  *(antes: StreamingTV - Yes/No/No internet service)*

- `Has_Streaming_Movies`: indica si tiene streaming de películas (True/False)  
  *(antes: StreamingMovies - Yes/No/No internet service)*

- `Contract_Type`: tipo de contrato (Month-to-month/One year/Two year)  
  *(antes: Contract)*

- `Uses_Paperless_Billing`: indica si usa facturación electrónica (True/False)  
  *(antes: PaperlessBilling - Yes/No)*

- `Payment_Method`: método de pago (Electronic check/Mailed check/Bank transfer/Credit card)  
  *(antes: PaymentMethod)*

- `Monthly_Charges`: cargos mensuales totales (en USD)  
  *(antes: Charges.Monthly)*

- `Total_Charges`: cargos totales acumulados (en USD)  
  *(antes: Charges.Total)*

- `Daily_Billing`: cargos diarios promedio calculados (Monthly_Charges/30)  
  *(nueva variable derivada)*

- `Service_Count`: cantidad total de servicios contratados (rango 0-8)  
  *(nueva variable derivada)*
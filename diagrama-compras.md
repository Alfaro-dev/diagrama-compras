# PROCESO DE COMPRAS - Diagrama de Flujo

```mermaid
flowchart TB
    subgraph ETAPA_1["📋 ETAPA 1: REQUERIMIENTO"]
        A1[📝 Elaboración requerimiento<br/>de materiales]
        A2[✅ Aprobación del jefe]
    end
    
    subgraph ETAPA_2["🔍 ETAPA 2: EVALUACIÓN Y SELECCIÓN"]
        B1[📊 Evaluación de propuestas]
        B2[👥 Selección de proveedores]
        B3[🤝 Negociación y contratación]
    end
    
    subgraph ETAPA_3["🛒 ETAPA 3: ADQUISICIÓN"]
        C1[📄 Elaboración orden<br/>de compra]
        C2[📨 Distribución orden<br/>de compra]
        C3[📦 Seguimiento de entrega]
    end
    
    subgraph ETAPA_4["📥 ETAPA 4: RECIBIMIENTO"]
        D1[📬 Recepción de mercadería]
        D2[🔎 Verificación de<br/>calidad y cantidad]
        D3[✅ Inspección]
    end
    
    subgraph ETAPA_5["💰 ETAPA 5: FACTURACIÓN Y PAGO"]
        E1[📨 Recepción de factura]
        E2[🔍 Revisión de factura]
        E3[✅ Verificación de<br/>calidad y cantidad]
        E4[✅ Verificación de<br/>proveedores]
        E5[💵 Liquidación y pago]
    end
    
    subgraph GESTIONES
        G1[🏦 Gestión de cartera<br/>y tesorería]
        G2[📦 Gestión de almacén<br/>e inventarios]
        G3[💳 Gestión financiera]
    end
    
    A1 --> A2
    A2 --> B1
    B1 --> B2
    B2 --> B3
    B3 --> C1
    C1 --> C2
    C2 --> C3
    C3 --> D1
    D1 --> D2
    D2 --> D3
    D3 --> E1
    E1 --> E2
    E2 --> E3
    E3 --> E4
    E4 --> E5
    
    A2 -->|"Salida"| G1
    E5 -->|"Salida"| G1
    D3 -->|"Salida"| G2
    E5 -->|"Salida"| G3
```

---

## Versión Simple - Lista de Pasos

### ETAPA 1: REQUERIMIENTO
1. Elaboración de requerimiento de materiales
2. Aprobación del jefe

### ETAPA 2: EVALUACIÓN Y SELECCIÓN
1. Evaluación de propuestas
2. Selección de proveedores
3. Negociación y contratación

### ETAPA 3: ADQUISICIÓN
1. Elaboración orden de compra
2. Distribución orden de compra
3. Seguimiento de entrega

### ETAPA 4: RECIBIMIENTO
1. Recepción de mercadería
2. Verificación de calidad y cantidad
3. Inspección

### ETAPA 5: FACTURACIÓN Y PAGO
1. Recepción de factura
2. Revisión de factura
3. Verificación de calidad y cantidad
4. Verificación de proveedores
5. Liquidación y pago

---

## Gestiones de Soporte
- **Gestión de cartera y tesorería** → Flujo desde Etapa 1 y Etapa 5
- **Gestión de almacén e inventarios** → Flujo desde Etapa 4
- **Gestión financiera** → Flujo desde Etapa 5

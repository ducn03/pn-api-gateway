# pn-api-gateway (Premier Nuts ERP - API Gateway)

Dịch vụ định tuyến API Gateway trung tâm cho hệ thống **Premier Nuts ERP**.

## 🛠 Công nghệ sử dụng
- **Framework:** Spring Boot 4.1.2
- **Java:** Java 27 (Tương thích bytecode Java 27 / LTS 21 & 17)
- **Spring Cloud:** Spring Cloud Gateway (Server WebMVC) 2025.1.4
- **Công cụ giám sát:** Spring Boot Actuator
- **Cổng mặc định (Port):** `8080`

## 🚀 Khởi chạy dự án

### Chạy bằng Maven Wrapper:
```powershell
./mvnw spring-boot:run
```

### Build file JAR:
```powershell
./mvnw clean package
```

### Health Check:
- URL: `http://localhost:8080/actuator/health`
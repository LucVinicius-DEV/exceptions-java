<p align="center">
  <img src="https://raw.githubusercontent.com/LucVinicius-DEV/exceptions1-java/main/banner.png" alt="Banner exceptions1-java" />
</p>

# Exceptions

Repositório criado durante o curso de Java do professor Nélio Alves.

Este projeto contém exemplos práticos sobre **tratamento de exceções em Java**, abordando:

- Blocos `try`, `catch`, `finally`
- Criação de exceções personalizadas
- Propagação de exceções com `throws`
- Boas práticas no uso de exceções

---

### 📁 Estrutura do projeto

```
exceptions1-java/
├── application/
│   └── Program.java
├── model/
│   └── entities/
│       └── Reservation.java
│   └── exceptions/
│       └── DomainException.java
```

---

### 💡 Conceitos aplicados

- **Try/Catch**: Captura e tratamento de erros em tempo de execução.
- **Finally**: Bloco executado independentemente de erro ou não.
- **Exceções Personalizadas**: Criação de classes que estendem `RuntimeException` para regras de domínio.
- **Validações**: Garantia de integridade nos dados da reserva de hotel.

---

### ✅ Exemplo de uso

```java
Reservation reservation = new Reservation(roomNumber, checkIn, checkOut);
System.out.println("Reservation: " + reservation);

reservation.updateDates(newCheckIn, newCheckOut);
System.out.println("Updated Reservation: " + reservation);
```

---

### 👨‍🏫 Professor

Este projeto foi desenvolvido com base nas aulas do [Prof. Nélio Alves](https://github.com/nelioalves), no curso de Java completo da Udemy.

---

### 🔗 Licença

Este repositório é apenas para fins de estudo e prática.

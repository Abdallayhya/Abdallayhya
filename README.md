<div align="center">
  
# 🚀 Abdalla Yahya | FullStack .NET Developer

### *Building scalable, clean, and high-performance web applications*

[![GitHub Followers](https://img.shields.io/github/followers/Abdallayhya?style=for-the-badge&logo=github&color=0d1117)](https://github.com/Abdallayhya)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/abdalla-yhya/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail)](mailto:abdallayhya77@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-000000?style=for-the-badge&logo=vercel)](https://my-portfolio-blue-iota-55.vercel.app/)

</div>

---

## 🎯 About Me

I'm a **FullStack .NET Developer** passionate about building **clean, maintainable, and scalable applications**. I believe in writing code that not only works but is also a pleasure to read and maintain.

- 🔭 Currently working on **Multi-Vendor Marketplace Platform**
- 🌱 Exploring **Microservices Architecture** & **Domain-Driven Design**
- 💬 Ask me about **Clean Architecture**, **Design Patterns**, or **ASP.NET Core**
- ⚡ Fun fact: I treat code like literature - it should tell a clear story

---

## 🛠️ Technical Stack

### Backend
| Technology | Proficiency | Projects |
|------------|-------------|----------|
| **ASP.NET Core MVC** | ⭐⭐⭐⭐⭐ | All projects |
| **ASP.NET Core Web API** | ⭐⭐⭐⭐⭐ | RESTful services |
| **Entity Framework Core** | ⭐⭐⭐⭐⭐ | ORM, migrations |
| **Clean Architecture** | ⭐⭐⭐⭐⭐ | Main architecture |
| **CQRS + MediatR** | ⭐⭐⭐⭐ | Command/Query separation |
| **SignalR** | ⭐⭐⭐⭐ | Real-time features |

### Frontend
| Technology | Proficiency | Projects |
|------------|-------------|----------|
| **React 18+** | ⭐⭐⭐⭐⭐ | SPA development |
| **TypeScript** | ⭐⭐⭐⭐⭐ | Type-safe code |
| **Tailwind CSS** | ⭐⭐⭐⭐⭐ | Utility-first styling |
| **Next.js** | ⭐⭐⭐⭐ | SSR, routing |
| **Redux Toolkit** | ⭐⭐⭐⭐ | State management |
| **React Query** | ⭐⭐⭐⭐ | Server state |

### Database & Tools
| Technology | Purpose |
|------------|---------|
| **PostgreSQL** | Primary database |
| **SQL Server** | Enterprise projects |
| **Redis** | Caching, sessions |
| **Git/GitHub** | Version control |
| **Docker** | Containerization |
| **Azure/AWS** | Cloud deployment |

---

## 🏗️ Architecture Philosophy

```csharp
// ✅ Clean Code - Meaningful names, small methods
public class OrderService : IOrderService
{
    public async Task<OrderResult> ProcessOrderAsync(OrderRequest request)
    {
        ValidateOrder(request);
        var order = CreateOrderFromRequest(request);
        await ApplyBusinessRulesAsync(order);
        return await PersistAndReturnResultAsync(order);
    }
}

// ✅ Design Patterns - Repository, Unit of Work, Strategy
public interface IRepository<T> where T : IAggregateRoot { /* ... */ }

// ✅ SOLID Principles - Single Responsibility, Open/Closed
// ✅ OOP - Encapsulation, Inheritance, Polymorphism
// ✅ RESTful APIs - Resource-based, stateless, proper status codes

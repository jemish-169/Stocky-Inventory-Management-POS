# Stocky - Inventory Management POS

## Features

- **User Onboarding & Authentication**  
  - User-friendly onboarding flow.  
  - Secure authentication using Supabase Auth.  

- **Dashboard Overview**  
  - View daily performance metrics.  
  - Displays total cash in, bills generated, and traded items for the day.

- **Inventory Module**  
  - Product listing with details: name, company, category, quantity, purchase & selling prices.  
  - Advanced search by product name, company, or category.
  - user can add item by giving relevant data.

- **Sales Module**  
  - Product listing with add-to-cart functionality.  
  - Customizable tax and discount percentages.  
  - Customer details input for each transaction.  
  - PDF invoice generation post transaction.

- **Account & Analytics**  
  - Month-wise data insights with interactive graphs.  
  - Daily breakdown showing traded items, bills generated, and cash inflow.

- **Transactions**  
  - Chronological list of all transactions.  
  - Detailed info: item, customer, payment mode, quantity, date, and time.
 
- **Theme and Language**
  - App has Multi-language support and feature to choose in app language.
  - Stocky has different theme mode like Dark, Light and System 

- **Concurrent Transactions with RPC**  
  - Uses Supabase RPC functions to ensure safe concurrent updates.  
  - Real-time sync for multi-user environments.

## Technology Stack

- **Android (Kotlin)** – Native development using Jetpack Compose.  
- **Supabase** – Backend as a service: Authentication, Database, Storage, and RPC.  
- **Jetpack Compose** – Declarative UI toolkit for modern Android apps.  
- **Coroutines** – Asynchronous and non-blocking programming.  
- **Hilt** – Dependency injection for scalable and maintainable architecture.  
- **MVVM + Clean Architecture** – Separation of concerns and testable codebase.  
- **Material Design** – Intuitive and consistent UI using Material components.  
- **Animations** – Smooth and meaningful transitions throughout the app.  

## Screenshots  

<table>
  <tr>
    <td align="center"><b>Authentication</b><br><img src="https://github.com/user-attachments/assets/ea7da6d5-cb1c-4cb8-bbc7-b988f1aa5fb1" width="250"/></td>
    <td align="center"><b>Home Screen</b><br><img src="https://github.com/user-attachments/assets/2d9be1b2-5296-4cf3-a6de-1c8143b26b65" width="250"/></td>
    <td align="center"><b>Sales Item Listing</b><br><img src="https://github.com/user-attachments/assets/c5f359fd-a712-4aae-9b29-14c3460556e1" width="250"/></td>
  </tr>
  <tr>
    <td align="center"><b>Gen. Customised Bill</b><br><img src="https://github.com/user-attachments/assets/d77bfc5d-a7a7-4e25-a07c-c8927b6efd3a" width="250"/></td>
    <td align="center"><b>Generated Invoice</b><br><img src="https://github.com/user-attachments/assets/8f5e3ea5-fe2c-41b9-8da5-9ecc1b9b8ff7" width="250"/></td>
    <td align="center"><b>Add Item Screen</b><br><img src="https://github.com/user-attachments/assets/3ece6258-e2fa-4a19-b2c3-6de6707bc20b" width="250"/></td>
  </tr>
  <tr>
    <td align="center"><b>Monthly Track</b><br><img src="https://github.com/user-attachments/assets/65654ac1-ec7e-4fbf-8810-bf2275fdb76b" width="250"/></td>
    <td align="center"><b>Transactions</b><br><img src="https://github.com/user-attachments/assets/64b81205-c273-431b-993f-1f709e2b3164" width="250"/></td>
    <td align="center"><b>App Settings</b><br><img src="https://github.com/user-attachments/assets/e52c5ff1-6304-4875-af22-1de4e1337bd4" width="250"/></td>
  </tr>
</table>

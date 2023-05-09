<div id="top"></div>

<table style="width:100%">
  <tr>
    <td>

## Shop Pal 🛒

<p align="left"> E-Commerce Android app built with Kotlin, Firebase, Room and MVC.</p>

<p align="left">
    <a href = "https://kotlinlang.org/docs/home.html">
      <img src = "https://img.shields.io/static/v1?style=for-the-badge&message=Kotlin&color=7F52FF&logo=Kotlin&logoColor=FFFFFF&label=" />
    </a>
    <a href = "https://firebase.google.com/">
      <img src = "https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white" />
    </a>
    <a href = "https://developer.android.com/training/data-storage/room">
      <img src = "https://img.shields.io/static/v1?style=for-the-badge&message=Room&color=003B57&logo=SQLite&logoColor=FFFFFF&label="/>
    </a>
    <a href = "https://developer.android.com/jetpack?gclid=EAIaIQobChMIpsz-h-3n_gIVxX99Ch0akwnJEAAYASAAEgJXhvD_BwE&gclsrc=aw.ds">
      <img src = "https://img.shields.io/static/v1?style=for-the-badge&message=Jetpack+Component&color=4285F4&logo=Jetpack+Compose&logoColor=FFFFFF&label="/>
    </a>
</p>

### The purpose of this repository

- A fully functional E-Commerce Android app built with Kotlin, Firebase and Room Database.
- Follows Android design and development best practices with MVC
- Explore the possibilities of creating a realtime application with complex UI and UX.

### Status: 👨‍💻 In progress

<p>ShopPal is under active development.</p>

</td> 
<td>

  <img src = "SS/1.png" width="240"/>
</td>
</tr>
</table>

### Stack

| Tools & Libraries| Link |
|     :---      |          :---: |
| 🤖 Kotlin | [Kotlin](https://kotlinlang.org) |](https://developer.android.com/jetpack/compose) |
|<img src = "https://cdn4.iconfinder.com/data/icons/google-i-o-2016/512/google_firebase-2-512.png" width="22"/> Firebase Authentication  | [Authentication](https://firebase.google.com/products/auth) |
| <img src = "https://seeklogo.com/images/F/firestore-logo-3828671CC5-seeklogo.com.png" width="15"/> Firebase Cloud Firestore | [Cloud Database](https://firebase.google.com/products/firestore) |
| <img src = "https://4.bp.blogspot.com/-I6KBH1NIJGk/XIccojn6YII/AAAAAAAADZ8/BeJ6uuutN5YoQe6Zboig_q5djnXS3hVpgCLcBGAs/s1600/Firebase%2BRealtime%2BDatabase%2B%25281-%2BIcon%252C%2BLight%2529.png" width="15"/> Firebase Realtime Database | [Realtime Database](https://firebase.google.com/products/realtime-database) |
|<img src = "https://www.devintent.com/assets/icons/firebase-storage-icon.png" width="18"/> Firebase Cloud Storage  | [Cloud Stroage](https://firebase.google.com/products/storage) |
| Room | [Database](https://developer.android.com/training/data-storage/room) |
| Navigation component | [Nav Graph](https://developer.android.com/guide/navigation/navigation-getting-started) |
| Glide | [Glide](https://github.com/bumptech/glide) |
| Gson | [GSon](https://github.com/google/gson) |


## 📷 Screenshots

<table style="width:100%">
  <tr>
    <th>Splash Screen</th>
    <th>Login</th> 
    <th>Registration</th>
    <th>Password Reset</th>
  </tr>
  <tr>
    <td><img src = "SS/1.png" width=240/></td> 
    <td><img src = "SS/2.png" width=240/></td>
    <td><img src = "SS/3.png" width=240/></td> 
    <td><img src = "SS/4.1.png" width=240/></td>
  </tr>
  <tr>
    <th>User Info Edit</th>
    <th>Dashboard</th>
    <th>Product Details</th>
    <th>Cart</th>
  </tr>
  <tr>
    <td><img src = "SS/4.2.png" width=240/></td>
    <td><img src = "SS/5.png" width=240/></td>
    <td><img src = "SS/6.png" width=240/></td>
    <td><img src = "SS/7.png" width=240/></td>
  </tr>
  <tr>
    <th>Cart</th>
    <th>Address</th> 
    <th>Delivery Details</th>
    <th>Checkout</th>
  </tr>
  <tr>
    <td><img src = "SS/8.png" width=240/></td> 
    <td><img src = "SS/9.png" width=240/></td>
    <td><img src = "SS/10.png" width=240/></td> 
    <td><img src = "SS/11.png" width=240/></td>
  </tr>
  <tr>
    <th>Order Status</th>
    <th>Ordered Item Info</th>
    <th>User Settings</th>
  </tr>
  <tr>
    <td><img src = "SS/12.png" width=240/></td>
    <td><img src = "SS/13.png" width=240/></td>
    <td><img src = "SS/14.png" width=240/></td>
  </tr>
</table>


 ## Package Structure
 
    com.example.shoppal                # Root Package
      .
      ├── activities                   # Contains various activities to login, register, add address, select address, implement cart functionality, checkout order, view shopping items, reset password, view details of the item, show status of the order, view/edit profile details and logout.
      ├── adapters                     # Contains adapters to manage the flow of the application.
      ├── firebase                     # Implements firebase authentication, firebase cloud firestore, firebase realtime database and firebase storage.  
      ├── fragments                    # Contains CartFragment, OrdersFragment and ShoppingItemsFragment to implement cart functionality, display status of orders and display shopping items.
      ├── interfaces                   # Has interface which contains setUserDetails method.
      ├── models                       # Contains various model classes to implement business layer of the application.
      ├── room                         # Implements room persistence library related logic.
      └── utils                        # Contains Constants/Tags
      

<p align="right">[<a href="#top">Back to top</a>]</p>

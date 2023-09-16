# Details

Date : 2023-09-16 12:51:43

Directory c:\\Users\\Developer\\Desktop\\My Projects\\proshop-v2

Total : 76 files,  38645 codes, 202 comments, 1714 blanks, all 40561 lines

[Summary](results.md) / Details / [Diff Summary](diff.md) / [Diff Details](diff-details.md)

## Files
| filename | language | code | comment | blank | total |
| :--- | :--- | ---: | ---: | ---: | ---: |
| [.prettierrc.yaml](/.prettierrc.yaml) | YAML | 9 | 0 | 1 | 10 |
| [backend/config/db.js](/backend/config/db.js) | JavaScript | 11 | 0 | 3 | 14 |
| [backend/controllers/orderController.js](/backend/controllers/orderController.js) | JavaScript | 105 | 29 | 25 | 159 |
| [backend/controllers/productController.js](/backend/controllers/productController.js) | JavaScript | 114 | 25 | 27 | 166 |
| [backend/controllers/userController.js](/backend/controllers/userController.js) | JavaScript | 141 | 27 | 28 | 196 |
| [backend/data/products.js](/backend/data/products.js) | JavaScript | 75 | 0 | 2 | 77 |
| [backend/data/users.js](/backend/data/users.js) | JavaScript | 20 | 0 | 3 | 23 |
| [backend/middleware/asyncHandler.js](/backend/middleware/asyncHandler.js) | JavaScript | 3 | 0 | 2 | 5 |
| [backend/middleware/authMiddleware.js](/backend/middleware/authMiddleware.js) | JavaScript | 30 | 3 | 8 | 41 |
| [backend/middleware/checkObjectId.js](/backend/middleware/checkObjectId.js) | JavaScript | 9 | 9 | 4 | 22 |
| [backend/middleware/errorMiddleware.js](/backend/middleware/errorMiddleware.js) | JavaScript | 14 | 2 | 5 | 21 |
| [backend/models/orderModel.js](/backend/models/orderModel.js) | JavaScript | 80 | 0 | 4 | 84 |
| [backend/models/productModel.js](/backend/models/productModel.js) | JavaScript | 71 | 0 | 5 | 76 |
| [backend/models/userModel.js](/backend/models/userModel.js) | JavaScript | 39 | 2 | 7 | 48 |
| [backend/routes/orderRoutes.js](/backend/routes/orderRoutes.js) | JavaScript | 17 | 0 | 3 | 20 |
| [backend/routes/productRoutes.js](/backend/routes/productRoutes.js) | JavaScript | 22 | 0 | 3 | 25 |
| [backend/routes/uploadRoutes.js](/backend/routes/uploadRoutes.js) | JavaScript | 40 | 0 | 10 | 50 |
| [backend/routes/userRoutes.js](/backend/routes/userRoutes.js) | JavaScript | 27 | 0 | 4 | 31 |
| [backend/seeder.js](/backend/seeder.js) | JavaScript | 46 | 0 | 12 | 58 |
| [backend/server.js](/backend/server.js) | JavaScript | 43 | 0 | 11 | 54 |
| [backend/utils/calcPrices.js](/backend/utils/calcPrices.js) | JavaScript | 16 | 4 | 2 | 22 |
| [backend/utils/generateToken.js](/backend/utils/generateToken.js) | JavaScript | 13 | 1 | 4 | 18 |
| [backend/utils/paypal.js](/backend/utils/paypal.js) | JavaScript | 51 | 29 | 12 | 92 |
| [frontend/README.md](/frontend/README.md) | Markdown | 38 | 0 | 33 | 71 |
| [frontend/package-lock.json](/frontend/package-lock.json) | JSON | 17,738 | 0 | 1 | 17,739 |
| [frontend/package.json](/frontend/package.json) | JSON | 50 | 0 | 1 | 51 |
| [frontend/public/index.html](/frontend/public/index.html) | HTML | 16 | 0 | 1 | 17 |
| [frontend/public/manifest.json](/frontend/public/manifest.json) | JSON | 25 | 0 | 1 | 26 |
| [frontend/src/App.js](/frontend/src/App.js) | JavaScript | 34 | 0 | 7 | 41 |
| [frontend/src/assets/styles/bootstrap.custom.css](/frontend/src/assets/styles/bootstrap.custom.css) | CSS | 11,245 | 31 | 845 | 12,121 |
| [frontend/src/assets/styles/index.css](/frontend/src/assets/styles/index.css) | CSS | 44 | 0 | 10 | 54 |
| [frontend/src/components/AdminRoute.jsx](/frontend/src/components/AdminRoute.jsx) | JavaScript JSX | 11 | 0 | 2 | 13 |
| [frontend/src/components/CheckoutSteps.jsx](/frontend/src/components/CheckoutSteps.jsx) | JavaScript JSX | 46 | 0 | 6 | 52 |
| [frontend/src/components/Footer.jsx](/frontend/src/components/Footer.jsx) | JavaScript JSX | 16 | 0 | 3 | 19 |
| [frontend/src/components/FormContainer.jsx](/frontend/src/components/FormContainer.jsx) | JavaScript JSX | 13 | 0 | 3 | 16 |
| [frontend/src/components/Header.jsx](/frontend/src/components/Header.jsx) | JavaScript JSX | 89 | 3 | 8 | 100 |
| [frontend/src/components/Loader.jsx](/frontend/src/components/Loader.jsx) | JavaScript JSX | 16 | 0 | 3 | 19 |
| [frontend/src/components/Message.jsx](/frontend/src/components/Message.jsx) | JavaScript JSX | 8 | 0 | 4 | 12 |
| [frontend/src/components/Meta.jsx](/frontend/src/components/Meta.jsx) | JavaScript JSX | 16 | 0 | 4 | 20 |
| [frontend/src/components/Paginate.jsx](/frontend/src/components/Paginate.jsx) | JavaScript JSX | 25 | 0 | 3 | 28 |
| [frontend/src/components/PrivateRoute.jsx](/frontend/src/components/PrivateRoute.jsx) | JavaScript JSX | 7 | 0 | 2 | 9 |
| [frontend/src/components/Product.jsx](/frontend/src/components/Product.jsx) | JavaScript JSX | 27 | 0 | 6 | 33 |
| [frontend/src/components/ProductCarousel.jsx](/frontend/src/components/ProductCarousel.jsx) | JavaScript JSX | 26 | 0 | 4 | 30 |
| [frontend/src/components/Rating.jsx](/frontend/src/components/Rating.jsx) | JavaScript JSX | 57 | 0 | 4 | 61 |
| [frontend/src/components/SearchBox.jsx](/frontend/src/components/SearchBox.jsx) | JavaScript JSX | 34 | 1 | 6 | 41 |
| [frontend/src/constants.js](/frontend/src/constants.js) | JavaScript | 5 | 2 | 1 | 8 |
| [frontend/src/index.js](/frontend/src/index.js) | JavaScript | 83 | 1 | 4 | 88 |
| [frontend/src/reportWebVitals.js](/frontend/src/reportWebVitals.js) | JavaScript | 12 | 0 | 2 | 14 |
| [frontend/src/screens/CartScreen.jsx](/frontend/src/screens/CartScreen.jsx) | JavaScript JSX | 108 | 2 | 8 | 118 |
| [frontend/src/screens/HomeScreen.jsx](/frontend/src/screens/HomeScreen.jsx) | JavaScript JSX | 53 | 0 | 5 | 58 |
| [frontend/src/screens/LoginScreen.jsx](/frontend/src/screens/LoginScreen.jsx) | JavaScript JSX | 73 | 0 | 16 | 89 |
| [frontend/src/screens/OrderScreen.jsx](/frontend/src/screens/OrderScreen.jsx) | JavaScript JSX | 231 | 13 | 23 | 267 |
| [frontend/src/screens/PaymentScreen.jsx](/frontend/src/screens/PaymentScreen.jsx) | JavaScript JSX | 51 | 0 | 9 | 60 |
| [frontend/src/screens/PlaceOrderScreen.jsx](/frontend/src/screens/PlaceOrderScreen.jsx) | JavaScript JSX | 146 | 0 | 10 | 156 |
| [frontend/src/screens/ProductScreen.jsx](/frontend/src/screens/ProductScreen.jsx) | JavaScript JSX | 214 | 1 | 16 | 231 |
| [frontend/src/screens/ProfileScreen.jsx](/frontend/src/screens/ProfileScreen.jsx) | JavaScript JSX | 148 | 0 | 15 | 163 |
| [frontend/src/screens/RegisterScreen.jsx](/frontend/src/screens/RegisterScreen.jsx) | JavaScript JSX | 97 | 0 | 17 | 114 |
| [frontend/src/screens/ShippingScreen.jsx](/frontend/src/screens/ShippingScreen.jsx) | JavaScript JSX | 76 | 0 | 11 | 87 |
| [frontend/src/screens/admin/OrderListScreen.jsx](/frontend/src/screens/admin/OrderListScreen.jsx) | JavaScript JSX | 67 | 0 | 4 | 71 |
| [frontend/src/screens/admin/ProductEditScreen.jsx](/frontend/src/screens/admin/ProductEditScreen.jsx) | JavaScript JSX | 171 | 0 | 19 | 190 |
| [frontend/src/screens/admin/ProductListScreen.jsx](/frontend/src/screens/admin/ProductListScreen.jsx) | JavaScript JSX | 106 | 0 | 10 | 116 |
| [frontend/src/screens/admin/UserEditScreen.jsx](/frontend/src/screens/admin/UserEditScreen.jsx) | JavaScript JSX | 95 | 0 | 12 | 107 |
| [frontend/src/screens/admin/UserListScreen.jsx](/frontend/src/screens/admin/UserListScreen.jsx) | JavaScript JSX | 89 | 0 | 6 | 95 |
| [frontend/src/setupTests.js](/frontend/src/setupTests.js) | JavaScript | 1 | 4 | 1 | 6 |
| [frontend/src/slices/apiSlice.js](/frontend/src/slices/apiSlice.js) | JavaScript | 8 | 0 | 3 | 11 |
| [frontend/src/slices/authSlice.js](/frontend/src/slices/authSlice.js) | JavaScript | 24 | 2 | 6 | 32 |
| [frontend/src/slices/cartSlice.js](/frontend/src/slices/cartSlice.js) | JavaScript | 49 | 4 | 8 | 61 |
| [frontend/src/slices/ordersApiSlice.js](/frontend/src/slices/ordersApiSlice.js) | JavaScript | 59 | 0 | 3 | 62 |
| [frontend/src/slices/productsApiSlice.js](/frontend/src/slices/productsApiSlice.js) | JavaScript | 71 | 0 | 3 | 74 |
| [frontend/src/slices/usersApiSlice.js](/frontend/src/slices/usersApiSlice.js) | JavaScript | 70 | 0 | 3 | 73 |
| [frontend/src/store.js](/frontend/src/store.js) | JavaScript | 15 | 0 | 3 | 18 |
| [frontend/src/utils/cartUtils.js](/frontend/src/utils/cartUtils.js) | JavaScript | 17 | 5 | 7 | 29 |
| [package-lock.json](/package-lock.json) | JSON | 4,228 | 0 | 1 | 4,229 |
| [package.json](/package.json) | JSON | 35 | 0 | 1 | 36 |
| [pnpm-lock.yaml](/pnpm-lock.yaml) | YAML | 1,334 | 0 | 235 | 1,569 |
| [readme.md](/readme.md) | Markdown | 332 | 2 | 110 | 444 |

[Summary](results.md) / Details / [Diff Summary](diff.md) / [Diff Details](diff-details.md)
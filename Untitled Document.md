1. TO TRACK LOGIN/FIRST VISIT OF ALL USERS
// Assuming you have a data layer object named ‘datalayer’
// Push Login event to data layer

datalayer. push
({‘event’: ‘Login’,
userId: ‘userId’,
Login Method: ’email/password’
});

2. TO TRACK PAGE VIEW
// Assuming you have a data layer object named ‘datalayer’
// Push Page View event to data layer
datalayer. push
({‘event’:’pageView’,
‘pageName’: //Current Page Title
‘pageUrl’: https://});

3. TO TRACK PAGE SCROLL
// Assuming you have a data layer object named ‘datalayer’
// Push Scroll event to data layer
datalayer. push
({‘event’: ‘Page Scroll’,
userId: ‘userId’,
scrollDepth: ‘50%’
});









4. TO TRACK PRODUCT VIEW
// Assuming you have a data layer object named ‘datalayer’
// Push Product view event to data layer
         dataLayer.push({
                event: 'productView',
              productId: 'product_id',
             productName: 'Product_name’
            categoryId: 'category_id',
            categoryName: 'Category_name',
                });

6. TO TRACK CLICK ON REVIEWS LINK
           // Assuming you have a data layer object named ‘datalayer’
          // Push Product view event to data layer
                dataLayer.push({
               event: 'reviewClick',
              productId: 'product_id',
             productName: 'Product_name’
            categoryId: 'category_id',
            categoryName: 'Category_name' });

5. TO TRACK PRODUCT VIEW
// Assuming you have a data layer object named ‘datalayer’
// Push Product view event to data layer
         dataLayer.push({
                event: 'productView',
              productId: 'product_id',
             productName: 'Product_name',
            categoryId: 'category_id',
            categoryName: 'Category_name',
                });

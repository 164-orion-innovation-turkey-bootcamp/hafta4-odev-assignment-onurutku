# Week4 Homework Project Live Link
("https://commerce-out.netlify.app/login")
# You-tube Project Explanation Video Link
("https://youtu.be/W5ubadZA9RA")

# Importan Note:
   ## Admin : username: admin@admin.com , password : Admin123
   You can login with this username and password if you want to check my project as admin or you can register with a random e-mail address to check the project as customer.

   <hr>

## Summary
   Hello There;
   On this e-commerce site that I coded for a week,
   I tried to use a modular structure in this e-commerce project. With TypeScript, I took care to assign types to all data types and also tried to take advantage of all the modules Angular offers us to increase the project performance.I would like to briefly talk about the features I use;

   <strong>Reactive Forms</strong>
   <strong>Custom Validations</strong>
   <strong>Fire Reader Library</strong>
   <strong>Route Guards</strong>
   <strong>Interceptors</strong>
   <strong>Resolvers</strong>
   <strong>Lazy Load(Preloading-Strategy)</strong>

   <hr>

   and also i used Google-Firebase backend-services for this project

   <strong>Firebase Auth Module</strong>
   <strong>Firebase Realtime Database Module</strong>
   <strong>Firebase Storage (store files)</strong>

   In this project as you can watch on youtube video, there is a user interface for a customer and a admin interface. Customers can buy see details of products and add products to their shoppin carts and checkout. Admin iterface can upload/delete products on website and check orders from customers checkouts to ship.

   <hr>

   <strong>Bootstrap</strong>
   <strong>Scss</strong>
   <strong>FontAwesome</strong>

   For styling i used Bootstrap,Scss and FontAwesome.During coding the project sometimes i need some special mediaqueries to make project real responsive. For example you can find that changes on login.component.scss file.

  ## Some SS from Project

<img
src='src/assets/register.jpg'
raw=true
alt='Subject Pronouns'
style='margin-right: 10px; width:600px; height:auto;'
/>

<img
src='src/assets/login.jpg'
raw=true
alt='Subject Pronouns'
style='margin-right: 10px; width:600px; height:auto;'
/>

<img
src='src/assets/shop.jpg'
raw=trueScss

<img
src='src/assets/cart.jpg'
raw=true
alt='Subject Pronouns'
style='margin-right: 10px; width:600px; height:auto;'
/>

<img
src='src/assets/detail.jpg'
raw=true
alt='Subject Pronouns'
style='margin-right: 10px; width:600px; height:auto;'
/>

## download and run
<hr>
1-install Angular CLI version 13 or 14
2-open a terminal and run
git clone "https://github.com/164-orion-innovation-turkey-bootcamp/hafta4-odev-assignment-onurutku.git"
3-run "npm install" to call node modules.
4-run "ng s --o"

# Thank You.





This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.1.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

4. Hafta ??devi
   ??r??n sat??????n??n, kullan??c?? kayd??n??n ve giri??inin yap??ld??????, web uygulamas?? geli??tirilecek.

Fonksiyoneliteler:

//??? Uygulama responsive tasar??m?? desteklemeli, mobil ve bilgisayar ekranlar??na uyumlu ??al????mal?? (ui component frameworkleri, libraryleri kullan??labilir)
//??? Kullan??c??lar uygulamaya ??ye olabilmeli ve giri?? yapabilmeli (json dosyas??na kay??t olu??turulup, json dosyas??ndan do??rulama yap??labilir, ya da ekstra bir api yaz??labilir)
//??? ??r??n kart??nda bulunmas?? gerekenler; ??r??nlerin resmi, ad??, a????klamas?? ve fiyat??
//??? ??r??n listesi ana sayfada g??sterilmeli, kullan??c??lar isterlerse ??r??nlerin detay??na, ??r??nlerin ??zerine t??klayarak bakabilmeli
//??? ??r??nlerin detay sayfas??nda, ??r??n??n daha b??y??k bir resmi ve daha detayl?? bir a????klama metni olmal??
//??? ??r??n detay??na gidilirken, sayfa y??nlendirilmesi (routing) yap??lmal??
//??? ??r??nler kendinizin belirleyece??i bir json kaynak dosyas??ndan al??nmal??

//Gereklilikler:
//??? Reactive form yakla????m?? kullan??lmal??
//??? Form i??lemlerinde validasyon y??netimi yap??lmal?? ve kullan??c?? dostu bir uyar?? mesaj?? ??retilmeli
//??? Http istekleri i??in HttpClient paketi kullan??lmal??
//??? Comment kullan??m??na dikkat edilmeli
//??? TypeScript ??zelliklerinden type ve access modifiers kullan??m??na dikkat edilmeli

//Ekstralar:
//??? ??r??nlerin detay k??sm??nda, ??r??n ile ilgili olu??turulacak dummy(sahte) yorumlar??n ve de??erlendirmelerin g??r??nt??lenmesi
//??? Component mimarisinin anla????l??r, tekrar kullan??labilecek ??ekilde kurgulanmas??

//Teknolojiler: Angular (13), JavaScript, TypeScript

//??? ??r??nlerin filtrelenmesi i??in; kategori se??ene??i (dropdown, selector, kategorileri siz belirlemelisiniz) ve bir arama ??ubu??u olu??turulmal??, anahtar kelimesinin ??r??n ad??nda ge??ip ge??medi??ine bak??lmal??
//??? ??r??nler sepete eklenip daha sonras??nda sat???? i??lemi ger??ekle??tirilmeli
//??? Sat???? i??lemi i??in ayr?? bir json dosyas??na log kayd?? at??lmas?? yeterli
//??? Kullan??c?? sisteme giri?? yapmadan ??r??nleri g??rmemeli

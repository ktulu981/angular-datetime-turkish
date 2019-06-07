# Angular 7 + ngbootstrap Türkçe'ye çevirme


npm install --save @ng-bootstrap/ng-bootstrap
komutu ile ng-bootstap'  iprojemize ekliyoruz.

app.module.ts dosyasında import kısmına 
imports: [NgbModule]
ekliyoruz.(Yukarıya referansını eklemeyi unutmayın "import {NgbModule} from '@ng-bootstrap/ng-bootstrap';")

turkishDatePickerI18.ts dosyasını oluşturun.

app.module.ts dosyasında providers kısmına;

 providers: [
      {provide: NgbDatepickerI18n, useClass: TurkishDatePickerI18}
   ]
   
   ekliyoruz. Hepsi bu kadar

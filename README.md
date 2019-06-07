# Angular 7 + ngbootstrap Türkçe'ye çevirme
ngbootstrap datetime picker Turkish

turkishDatePickerI18.ts dosyasını oluşturun.

app.module.ts dosyasında providers kısmına;

 providers: [
      {provide: NgbDatepickerI18n, useClass: TurkishDatePickerI18}
   ]
   
   ekliyoruz. Hepsi bu kadar

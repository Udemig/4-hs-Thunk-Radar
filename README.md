# Kütüphaneler

- leaflet
- react-leaflet
- react-redux
- @reduxjs/toolkit
- axios
- thunk (toolkitin yanında gelicek)

# Kaynaklar

# Yapılcakalar

- Liste görünümü için `ListView.jsx` dosyası oluştur
- Harita görünümü için `MapView.jsx` dosyası oluştur
- `App.jsx ` içerisinde bu iki görünüm arasında geçişi sağla
- `MapView.jsx` harita kurulumu yap
- toolkit ile store kurulumu yap

- Uygulama ekrana geldiği anda Api'den Türkiye Üzerinde uçan çek ve store'a aktar

- - bize dizi içierisnde dizi geliyor
- - Eliimde Olan : [
    [123123,hsdf678,14.123,56.1234]
    [123123,hsdf678,14.123,56.1234]
    [123123,hsdf678,14.123,56.1234]
    ]
- - Elde Etmek İstediğim : [
    {
    id : "123123"
    code: "hsdf678",
    lat: 14.123
    lng: 56.1234
    }
    ]

- - uçaklar dizisi içerisindeki dizilerin enlem boylam id kurukkodu değerlerini al ve bu değerlerle bir obje oluştur.
- - bu işlem dizideki hergbir eleman için tekrarla(map)

- `MapView.jsx` 'de Store'da tutulan Uçuşlar disizindeki herbir obje için ekrana bir tane imleç (marker) bas
- - marker' position olarak obje içisindeki lat ve lng değerlerini ver
- - haritanın merkezini Kırşehir yap

- Popup içerisindeki Detay butonuna tıklanınca `SideDetail.jsx` bileşenini ekrana bas ve bileşen hangi uçağın detayı gösterilicekse onu aktar

- - Prop olarak gelen uçağın id değerini al ve bununla beraber api'ye istek at

- `ListView.jsx` içerisinde uçuşları tablo olarak listele

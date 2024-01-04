# solar-panel-project
Güneşe doğru yönelen güneş paneli

Bu projede bir güneş panelinin konumunu güneşin pozisyonuna göre otomatik olarak ayarlayabilen bir kontrol sistemi tasarlamak amaçlanmaktadır. Bu sistem güneş ışığından aldığı enerji ile pil şarj etmekte ve böylece elektrik tasarrufu sağlamaktadır. Bu şekilde batarya yönetim sistemi oluşturulmaktadır.

STM32 batarya yönetimi kontrolü için basit bir web sitesi tasarımı gerçekleştirilmiştir. Bunun için ESP32 modülü kullanılmıştır. Belirtilen kullanıcı adı ve wifi şifresi ile seri port üzerinden görüntülenen IP değeri ile batarya yüzdeleri görüntülenebilmektedir.

<h3>Kullanılan Malzemeler</h3>
<img src="https://github.com/dilarabukerr/solar-panel-project/blob/main/kullan%C4%B1lan_malzemeler.png" alt="Kullanılan malzemeler" width="600" height="400">

<h3> Devre Şeması Çizimi </h3>
<img src="https://github.com/dilarabukerr/solar-panel-project/blob/main/devre_semas%C4%B1.png" alt="devre şeması çizimi" width="900" height="500">

<h3> Sonuç </h3>
<img src="https://github.com/dilarabukerr/solar-panel-project/blob/main/devre2.png" alt="devre", mg src="https://github.com/dilarabukerr/solar-panel-project/blob/main/server.png" alt="server"> 

Sonuç olarak bu sistemde güneş paneli üzerinde bulunan iki adet LDR sensör ile ışık seviyeleri ölçülür. Hangi tarafta ışık daha fazla ise servo motor o tarafa döner. Güneş paneli ile ışıktan enerji alınır ve BMS devresi ile pil şarj edilir. ESP32 modülü sayesinde ise pilin kalan enerjisi ölçülür ve belirlenen IP adresi ile kullanıcıya gösterilir.

<img src="https://github.com/dilarabukerr/solar-panel-project/blob/main/server.png" alt="server">



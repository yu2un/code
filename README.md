# Ufak Tefek Kodlar

Kodlar burada yer alacak;

Class A
{
  public isim;
  public function __construct()
  {
    $this->isim = "İsim"; // $_GET , $_POST
  }
  public function ad()
  {
    echo $this->isim; // Çıktı İsim
    $this->isim = "Soyisim";
  }
  public function soyad()
  {
    echo $this->isim; // Çıktı Soyisim
  }
}

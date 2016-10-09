#### Ufak Tefek Kodlar

##### Class içi global değişken
```
<?
	class MyTest
	{
	    protected $a; //public , private , protected

	    public function __construct($a)
	    {
	        $this->a = $a;
	    }

	    public function head()
	    {
	        echo $this->a." - head /";
	    }

	    public function footer()
	    {
	        echo $this->a." - footer";
	    }
	}
	$a = "value" ; // $_POST["name"] $_GET["name"];
	$obj = new MyTest($a);$obj->head();$obj->footer(); // Çıktı : value - head / value - footer
?>
```

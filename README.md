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
#### Sef link id 

```
while(1){
            $uri_rows = $this->db->get_where('links', array('link_uri' => $uri))->num_rows();
            if($uri_rows>0){
                $uri_array = explode('-', $uri);
                if(is_numeric(end($uri_array))){
                    $last = end($uri_array);
                    array_pop($uri_array);
                    array_push($uri_array, ++$last);
                }else{
                    array_push($uri_array, 2);
                }
                $uri = implode('-', $uri_array);
            }else{
                break;
            }
        }
	
	```

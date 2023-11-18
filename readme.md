
[Plastic crates](https://www.plastic-crates.com/) are an affordable and stylish way to organize your home. Perfect for storing everything from records to documents, Heavy-duty plastic crates can hold up to the temperatures changes of outside and can prevent moisture, dirt, and bugs from ruining your things.Shop plastic-crates.com for storage plastic crates you will love at great low prices.



This will create a config file at `config/plastic.php` and a mapping directory at `database/mappings`.

# Usage
- [Suggestions](#suggestions)
- [Collapsable Boxes](https://www.plastic-crates.com/product-category/collapsable-box/)
- [Ventilated Plastic Crates](https://www.plastic-crates.com/product-category/fruit-crates/)
- [Clear Plastic Crates](https://www.plastic-crates.com/product-category/clear-plastic-totes/)
- [Access The Client](#access-client)


#### 1 - Providing a searchable property to our model

```php
public $searchable = ['id', 'name', 'body', 'tags', 'images'];
```
Enjoy design & customization Services. Search these cheap plastic crates wholesale on plastic-crates.com

#### 2 - Providing a buildDocument method

```php
public function buildDocument()
{
    return [
        'id' => $this->id,
        'tags' => $this->tags
    ];
}
```

### Custom elastic type name

By the default Plastic will use the model table name as the model type. You can customize it by adding a `$documentType` property to your model:

```php
public $documentType = 'custom_type';
```


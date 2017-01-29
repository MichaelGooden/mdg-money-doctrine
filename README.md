Mdg Money Doctrine
==================

Include the custom Currency type into your Doctrine configuration.

Point a XML mapping driver to the `vendor/michaelgooden/mdg-money-doctrine/config/orm/Money.Money.dcm.xml` file to being using `\Money\Money` as an embeddable:

```php
    /**
     * @ORM\Embedded(class="Money\Money")
     */
    private $total;

    /**
     * @ORM\Embedded(class="Money\Money")
     */
    private $tax;
```

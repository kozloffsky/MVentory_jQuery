mVentory_jQuery is a satellite Magento extension with jQuery files for other mVentory Magento extensions.

Its only action is placing jQuery files in `<magento_root>/js/jquery` folder.

This extension is required for [API](/mVentory/MVentory_Tm) and [Productivity](/mVentory/mvProductivity) extensions.

Currently used version of jQuery: 1.8.3

#### Referencing the jQuery files

This extension creates a magento layout handle called `jquery` in _frontend_ and _admin_ layout areas.

The handle can be invoked by insertting the following reference into a layout file:

    <catalog_product_view>
     <update handle="jquery" />
    </catalog_product_view>




 Curtain PDP - Shopify Theme Development Task

Features Implemented
 Dynamic pricing based on Width + Drop + Fabric Panels  
 Fabric Panels hidden from frontend  
 Real-time price updates without page refresh  
 Mobile responsive design  
 Clean, modular code structure  

1. Import attached theme file;
2. Import product csv
3. Ensure product has correct metafields: width_mapping(type json),pricing_table(type json)
4. Test on product page

 Pricing Logic
1. User selects Width (100/150/200 cm)
2. System calculates Fabric Panels: 100cm=1, 150cm=2, 200cm=3
3. User selects Drop (180/200 cm)
4. Price = pricing_table[panels][drop]
5. Price updates instantly on Add to Cart button

 Demo
https://curtain-pdp-dev.myshopify.com/
password: huzpdp
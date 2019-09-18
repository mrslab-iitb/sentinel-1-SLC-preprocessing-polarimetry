For single-date processing:
1. Run all the .xml files one by one

For multi-date processing:
1. Run module1_single_or_multi_date.xml file in batch mode to calibrate all the images at once
2. Run module2_multi_date.xml to coregister all the images
3. Run module3_single_or_multi_date.xml on the stack product
4. Manually delete baseline information from the metadata
5. Execute the "Stack Split" step manually
6. Run the module4_single_or_multi_date.xml in batch mode to export all split products to PolSARPro format

Reference:

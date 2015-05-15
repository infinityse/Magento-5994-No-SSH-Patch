# Magento-5994-No-SSH-Patch
The Magento 5994 patch that doesn't require SSH access to run the Magento supplied shell script. Magento CE 1.6 > 1.9 & Magento EE.

# Installation
Copy the supplied folders into the root directory of your Magento installation and overwrite the existing files.

# Files effected
app/code/core/Mage/Authorizenet/controllers/Directpost/PaymentController.php
app/code/core/Mage/Core/Controller/Varien/Router/Admin.php
app/code/core/Mage/Core/Controller/Varien/Router/Standard.php
app/code/core/Mage/Customer/Model/Customer.php
app/code/core/Mage/Dataflow/Model/Convert/Parser/Csv.php
app/code/core/Mage/ImportExport/Model/Export/Adapter/Csv.php
app/code/core/Mage/Install/Controller/Router/Install.php
app/code/core/Mage/Install/etc/config.xml
app/code/core/Mage/Sales/controllers/Recurring/ProfileController.php
downloader/Maged/Model/Connect.php
downloader/Maged/View.php
downloader/template/connect/packages_prepare.phtml
downloader/template/messages.phtml
get.php
lib/PEAR/PEAR/PEAR.php
lib/PEAR/PEAR/PEAR5.php
lib/Varien/Io/File.php

# common-lib

you have to create settings.xml as below

<?xml version="1.0"?>
<settings xmlns="http://maven.apache.org/SETTINGS/1.0.0"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/SETTINGS/1.0.0 http://maven.apache.org/xsd/settings-1.0.0.xsd">

<servers>
<server>
    <id>anypoint-exchange</id>
    <username>XXXX</username>
    <password>XXXX</password>
</server>
<server>
    <id>mulesoft-release</id>
    <username>XXXX</username>
    <password>XXXX</password>
</server>
<server>
    <id>anypoint-exchange-v3</id>
    <username>XXXX</username>
    <password>XXXX</password>
</server>

</servers>
</settings>

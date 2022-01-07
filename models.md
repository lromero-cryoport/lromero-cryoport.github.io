# My Table of content
- [Section 1](#models)
- [Section 1](#models-4)
- [Section 2](#user)
- [Section 3](#controllers)


- [Index](index.md)
- [Terms](terms.md)

## Models Pre


<div id='models-1'/>
## Models 1






<a href="#models-2">Models 2</a>	

<a href="#models-3">
## Models 3
</a>	


### Models 4 {#models-4}

====================================
<div id='user'/>
## User
User

  Why do we need has_many client_users



  ETHON: Libcurl initialized
ETHON: performed EASY effective_url=http://127.0.0.1:9200/ response_code=200 return_code=ok total_time=0.188105


Dewar

Bin Parts are in a Bin

A Bin is in a Facility

A Part is the type of Part that it is. <= Seed Data

Types of parts:
  Accessory
  BatteryModel
  BottleModel
  DataLoggerModel
  DewarModel
  Discount
  EnclosureModel
  FixedPriceDiscount
  FixedPriceFee
  LegFee
  LogisticsFee
  PackagingMaterial
  PartSet
  Refund
  Service
  ShipmentServiceFee
  Shipper
  ShipperManagementFee
  ThermocoupleModel


A lot of the Part Types have a corresponding model (without the "Model" suffix). These are
"Backing" (they mix in IsBacking)

IsBacking
## Attach any model with an inventory model.

Bottle
DataLogger
Enclosure
Battery
Thermocouple
Dewar



LoadTest - environment used by testing team in India.
LoadTest - environment used by testing team in India.
LoadTest - environment used by testing team in India.
LoadTest - environment used by testing team in India.
LoadTest - environment used by testing team in India.

Mega Menu
  Drop Menu in Cryoportal - where you see "Orders", etc etc


Shipper
  Collection of items

  Has a dewar attached to it
  Has a bunch of accessories

  Set Temperature alarms on it, etc


Dewar goes inside Enclosure


Verify Location
  Open the map, move the pin a little, and verify again.

Logistics Manager
  Usually creates the order.

CIC - "Client Integrated" - user


Pricing Approval - not required for all users

Two scenarios:
  Client creates their own.

  Cryoport creates it for the client


Workflow:
  1. Customer Service Rep Creates an Order.
  2. Logistics Manager Approves the Order.
    Scheduling takes place here.
    Pickup for Leg 1 is automatic.

    80% of the orders are charged through the Cryoport FedEx account.

    waybills


Status => Unsubmitted => Approval => Processing aka Assembling


Future Processing vs. Processing
  pickup_date condition

Need to assign each Shipper to a user


The shipper is a list of parts.


Pa

BinPartsController
  Literally in a bin in a facility


backing_state - attribute on device


Processing and Assembling may be synonyms

Mega Menu
  Drop Menu in Cryoportal - where you see "Orders", etc etc


Shipper
  Collection of items

  Has a dewar attached to it
  Has a bunch of accessories

  Set Temperature alarms on it, etc


Dewar goes inside Enclosure


Verify Location
  Open the map, move the pin a little, and verify again.

Logistics Manager
  Usually creates the order.

CIC - "Client Integrated" - user


Pricing Approval - not required for all users

Two scenarios:
  Client creates their own.

  Cryoport creates it for the client


Workflow:
  1. Customer Service Rep Creates an Order.
  2. Logistics Manager Approves the Order.
    Scheduling takes place here.
    Pickup for Leg 1 is automatic.

    80% of the orders are charged through the Cryoport FedEx account.

    waybills


Status => Unsubmitted => Approval => Processing aka Assembling


Future Processing vs. Processing
  pickup_date condition

Need to assign each Shipper to a user


The shipper is a list of parts.


Pa

BinPartsController
  Literally in a bin in a facility


backing_state - attribute on device


Processing and Assembling may be synonyms

Mega Menu
  Drop Menu in Cryoportal - where you see "Orders", etc etc


Shipper
  Collection of items

  Has a dewar attached to it
  Has a bunch of accessories

  Set Temperature alarms on it, etc


Dewar goes inside Enclosure


Verify Location
  Open the map, move the pin a little, and verify again.

Logistics Manager
  Usually creates the order.

CIC - "Client Integrated" - user


Pricing Approval - not required for all users

Two scenarios:
  Client creates their own.

  Cryoport creates it for the client


Workflow:
  1. Customer Service Rep Creates an Order.
  2. Logistics Manager Approves the Order.
    Scheduling takes place here.
    Pickup for Leg 1 is automatic.

    80% of the orders are charged through the Cryoport FedEx account.

    waybills


Status => Unsubmitted => Approval => Processing aka Assembling


Future Processing vs. Processing
  pickup_date condition

Need to assign each Shipper to a user


The shipper is a list of parts.


Pa

BinPartsController
  Literally in a bin in a facility


backing_state - attribute on device


Processing and Assembling may be synonyms

Mega Menu
  Drop Menu in Cryoportal - where you see "Orders", etc etc


Shipper
  Collection of items

  Has a dewar attached to it
  Has a bunch of accessories

  Set Temperature alarms on it, etc


Dewar goes inside Enclosure


Verify Location
  Open the map, move the pin a little, and verify again.

Logistics Manager
  Usually creates the order.

CIC - "Client Integrated" - user


Pricing Approval - not required for all users

Two scenarios:
  Client creates their own.

  Cryoport creates it for the client


Workflow:
  1. Customer Service Rep Creates an Order.
  2. Logistics Manager Approves the Order.
    Scheduling takes place here.
    Pickup for Leg 1 is automatic.

    80% of the orders are charged through the Cryoport FedEx account.

    waybills


Status => Unsubmitted => Approval => Processing aka Assembling


Future Processing vs. Processing
  pickup_date condition

Need to assign each Shipper to a user


The shipper is a list of parts.


Pa

BinPartsController
  Literally in a bin in a facility


backing_state - attribute on device


Processing and Assembling may be synonyms

Mega Menu
  Drop Menu in Cryoportal - where you see "Orders", etc etc


Shipper
  Collection of items

  Has a dewar attached to it
  Has a bunch of accessories

  Set Temperature alarms on it, etc


Dewar goes inside Enclosure


Verify Location
  Open the map, move the pin a little, and verify again.

Logistics Manager
  Usually creates the order.

CIC - "Client Integrated" - user


Pricing Approval - not required for all users

Two scenarios:
  Client creates their own.

  Cryoport creates it for the client


Workflow:
  1. Customer Service Rep Creates an Order.
  2. Logistics Manager Approves the Order.
    Scheduling takes place here.
    Pickup for Leg 1 is automatic.

    80% of the orders are charged through the Cryoport FedEx account.

    waybills


Status => Unsubmitted => Approval => Processing aka Assembling


Future Processing vs. Processing
  pickup_date condition

Need to assign each Shipper to a user


The shipper is a list of parts.


Pa

BinPartsController
  Literally in a bin in a facility


backing_state - attribute on device


Processing and Assembling may be synonyms






<div id='controllers'/>
## Controllers 



this is where the controllers are

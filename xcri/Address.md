#Address 

##Specification

*URI*: 

*Definition*: Additional address information.

*Type*: String

*Namespace*: This is defined within the namespace:

##Example
      
           The College of Art, Bolton
           Deane Road
           Bolton
           BL3 1EX
           
               -123.7
               54
      
##Guidance Notes

1.  **Vocabularies**: This type should be refined using specific address
    vocabulary terms.
2.  **Use of VCard:** attention is drawn to the VCard specification as a
    source of normative vocabulary for these elements.
3.  **Geocoding**: Providers MAY use "geo\_lat" and "geo\_long" as typed
    address lines to send geocode information; however, it is more
    likely that aggregators will perform a lookup on the
    [postcode](postcode.md).

##Usage

Address is used in instances of
[Organisation](Category%253AOrganisation_Types.md).

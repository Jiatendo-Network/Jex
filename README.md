## JEX LIBRARY WRITTEN IN RUST 

 JEX (which is Jiatendo Network's NEX) Library is the networking library used by all 1st party, and many 3rd party, games on the Nintendo Wii U, 3DS, and Switch which have online features. The NEX library has many different parts, ranging from low level packet transport to higher level service implementations

 This library implements the lowest level parts of NEX, the transport protocols. For other parts of the NEX stack, see the below libraries. This libary is the most advanced NEX Library in the history of Nintendo made with Rust Programming.

 ## Quazal Rendez-Vous
 
 Nintendo did not make NEX from scratch. NEX is largely based on an existing library called Rendez-Vous (QRV), made by Canadian software company Quazal. Quazal licensed Rendez-Vous out to many other companies, and was eventually bought out by Ubisoft. Because of this, QRV is seen in many many other games on all major platforms, especially Ubisoft

Nintendo modified Rendez-Vous somewhat heavily, simplifying the library/transport protocol quite a bit, and adding several custom services

While the main goal of this library is to support games which use the NEX variant of Rendez-Vous made by Nintendo, we also aim to be compatible with games using the original Rendez-Vous library. Due to the extensible nature of Rendez-Vous, many games may feature customizations much like NEX and have non-standard features/behavior. We do our best to support these cases, but there may be times where supporting all variations becomes untenable. In those cases, a fork of these libraries should be made instead if they require heavy modification

## All features are fully supported 

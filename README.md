# minecraft-protocol-documentation
Automatically generated documentation for Minecraft Bedrock Edition posted once a release or a beta is released.

Please keep in mind that in some case (as the LoginPacket) the protocol documentation is incomplete because the data comesfrom a objdump of libminecraftpe.so.

**Note:** When there is a difference between the write and the read method, for exemple for the TakeItemEntityPacket, just believe the method used by the packet in his normal behavior. In the case of the TakeItemEntityPacket it's a packet only sent by the server to the client and not the reverse. Same for other packets like the SetLastHurtByPacket or the ShowProfilePacket.

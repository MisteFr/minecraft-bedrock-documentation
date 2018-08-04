# minecraft-protocol-documentation
Automatically generated protocol documentation, symbols list and entity ids list for Minecraft Bedrock Edition posted once a release or a beta is released by [BedrockUpdateBot](https://github.com/MisteFr/BedrockUpdateBot).

For each version released, you can find a diff comparing what was found in this version compared to the latest version that can let you know if there are some protocol changes, some news symbols added or new entities added.

#### Concerning the protocol documentation
Please keep in mind that in some case (as the LoginPacket) the protocol documentation is incomplete because the data comes from a objdump of libminecraftpe.so.

**NB:** When there is a difference between the write and the read method, for exemple for the TakeItemEntityPacket, just believe the method used by the packet in his normal behavior. In the case of the TakeItemEntityPacket it's a packet only sent by the server to the client and not the reverse. Same for other packets like the SetLastHurtByPacket or the ShowProfilePacket.

As of today, the SONiC offical github <https://github.com/Azure/sonic-buildimage> does not release the SAI's library to support TD3. This image with SAI's library was ported by DNI and it is NOT the SONiC offical released SAI library


--- How to come out the onl image ---

In linux command modee, using following command to make up the image

# cat sonic-broadcom.tar.bz2.part* > sonic-broadcom.tar.bz2

# tar -jxvf sonic-broadcom.tar.bz2

Then you could install "sonic-broadcom.bin" like ONIE's NOS .

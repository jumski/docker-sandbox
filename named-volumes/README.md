# Named local volumes

If one want to use named volume in compose but to have this named volume
on host system specified as a concrete directory, one would create it as follows:

docker volume create --name my_test_volume --opt type=none --opt device=/home/jinna/Jinna_Balu/Test_volume --opt o=bind

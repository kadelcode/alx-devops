- Create a magic file ```school.mgc``` that can be used with the command ```file```to detect ```School``` data files. ```School``` data files always contain the string ```SCHOOL``` at offset 0.

- The magic file is compiled using the command:
	- ```file -C -m school.mgc```

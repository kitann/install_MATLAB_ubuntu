DOWNLOADER.GA -> Installation
------------^0o0^------------

0. Download then extract files.
Method 1: 
             unzip <name of zip file>
Then enter the password: downloader.ga if be required
Method 2: Right click on zip file, select extract here
1. Mount ISO:

sudo mount MatlabR2018b_LinuxX64_DVD1_downloader.ga.iso /cdrom -o loop
(
	if not folder 'cdrom' in 'Computer' then need to create it first:
		sudo mkdir -p /cdrom
)

2. Run installer:

	sudo /cdrom/install

3. Select Use File Installation Key.

4. Select I have Installation Key for my license and provide:

	09806-07443-53955-64350-21751-41297

To install Matlab Production Server,using this
	40236-45817-26714-51426-39281

5. Install into folder: /usr/local/MATLAB/R2018b

6. Wait for request of DVD2:

	sudo umount /cdrom
	sudo mount MatlabR2018b_LinuxX64_DVD2_downloader.ga.iso /cdrom -o loop

7. Continue with installation and wait for finish.

8. Replace bin folder:

	sudo cp -R Matlab\ R2018b\ Linux64\ Crack\ Only/bin /usr/local/MATLAB/R2018b/

8. Run MATLAB for the first time:

	sudo /usr/local/MATLAB/R2018b/bin/matlab

9. Select Activate manually without Internet and provide:

	Matlab R2018b Linux64 Crack Only/license_standalone.lic

The license will appear in /usr/local/MATLAB/R2018b/licenses.

10. Run activated MATLAB:

sudo /usr/local/MATLAB/R2018b/bin/matlab

Enjoy MATLAB! Or think about numpy/scipy or Octave :)

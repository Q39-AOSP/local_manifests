Q39 for AOSP-CAF
===========

Getting Started
---------------

You will need add codeaurora.org in hosts.

China Unicom: 61.49.51.109	codeaurora.org

China Telecom: 101.226.197.144	codeaurora.org

China Mobile: 119.9.118.43	codeaurora.org

To get started with AOSP CAF, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using the AOSP CAF trees, use a command like this:

	repo init -u git://codeaurora.org/platform/manifest.git -b release -m LA.BR.1.2.9-01810-8x16.0.xml --repo-url=git://codeaurora.org/tools/repo.git --repo-branch=caf-stable

	git clone https://github.com/lrinQVQ/local_manifests.git .repo/

Started Building
---------------

	source build/envsetup.sh

	lunch q39-userdebug

	make -j4

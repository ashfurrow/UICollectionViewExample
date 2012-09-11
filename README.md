UICollectionViewExample
=======================

To run this example, you *must* run the following command:

    git clone --recursive git://github.com/AshFurrow/UICollectionViewExample.git

This will retrieve the submodules required by the library.

Go to 500px to [register an application](http://developers.500px.com/settings/applications?from=developers) to get a consumer key and consumer secret. Open `AFMasterViewController.m` and change the following line.

    [PXRequest setConsumerKey:@"consumer key here" consumerSecret:@"consumer secret here"];

Build and run. Enjoy!

![UICollectionView Example App](http://static.ashfurrow.com.s3.amazonaws.com/github/UICollectionViewExample.png)

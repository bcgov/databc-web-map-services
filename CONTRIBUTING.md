##How to contribute
I'm really glad you're reading this, because we need developers to help this project come to fruition.

(If you are new to GitHub, you might start with a [basic tutorial](https://help.github.com/articles/set-up-git) and  check out a more detailed guide to [pull requests](https://help.github.com/articles/using-pull-requests/).)

## Pay for pull
We are using a "pay for pull" model for some of the issues in this repository. For issues labelled with a “Help Wanted” AND a “$ Amount" we will pay a flat dollar amount if we merge your contribution. 

Please read the [Rapid Adoption Guide](https://github.com/BCDevExchange/rapid-adoption/wiki) for everything you need to know to participate in a Pay for Pull.

For your pull request to be considered for payment, you must include a copy of the Terms completed with your information and a PayPal email link in the comments section of the of the pull request. Please read the Pay for Pull [Terms](https://github.com/bcgov/citizen-engagement-web-toolkit/blob/master/TERMS.md). 

## Testing


##Pull Requests

Issuing a pull request requires that you fork both this repository with the Terms and the GeoServer git repository for the code to into your own account.

Assuming that origin points to your GitHub repository then the workflow becomes:

Make the change.
   git checkout -b my_bugfix master
   git add .
   git commit -m "fixed bug xyz"
Push the change up to your GitHub repository.
   git push origin my_bugfix
Visit your GitHub repository page and issue the pull request to this reposo.

At this point the government technical contact  will be notified of the pull request and review it at the earliest convenience. Upon review they might require changes or improvements to it; it will be up to the submitter to amend the pull request and keep it alive until it gets merged.


##Commit Guidelines

Please send a GitHub Pull Request with a clear list of what you've done (read more about [pull requests](http://help.github.com/pull-requests/)). Please follow our coding conventions below and make sure all of your commits are atomic (one feature per commit).

Always write a clear log message for your commits. One-line messages are fine for small changes, but bigger changes should look like this:

    $ git commit -m "A brief summary of the commit
    > 
    > A paragraph describing what changed and its impact."

There is not much in the way of strict commit policies when it comes to committing in GeoServer. But over time some rules and conventions have emerged:

Update copyright headers: When adding new source files to the repository remember to add the standard copyright header:

/* (c) 2014 Open Source Geospatial Foundation - all rights reserved
* This code is licensed under the GPL 2.0 license, available at the root
* application directory.
*/
When updating a file .. update the header:

/* (c) 2013-2014 Open Source Geospatial Foundation - all rights reserved
* This code is licensed under the GPL 2.0 license, available at the root
* application directory.
*/
When adding content from another organisation maintain copyright history and original license. Only add (c) OSGeo if you have made modifications to the file for GeoServer:

/* (c) 2014 Open Source Geospatial Foundation - all rights reserved
* (c) 2014 OpenPlans
* (c) 2008-2010 GeoSolutions
* 
* This code is licensed under the GPL 2.0 license, available at the root
* application directory.
* 
* Original from GeoWebCache 1.5.1 under a LGPL license 
*/
In a rare case (as when asking to migrate content from GeoTools) you can obtain permission to change the license to our GPL 2.0 license.

Do not commit large amounts of binary data: In general do not commit any binary data to the repository. There are cases where it is appropriate like some data for a test case, but in these cases the files should be kept as small as possible.

Do not commit jars or libs, use Maven instead: In general never commit a depending library directly into the repository, this is what we use Maven for. If you have a jar that is not present in any maven repositories, ask on the developer list to get it uploaded to one of the project maven repositories.

Ensure code is properly formatted: Ensure that the IDE or editor used to edit source files is setup with proper formatting rules. This means spaces instead of tabs, 100 character line break, etc...

If using Eclipse ensure you have configured it with the template and formatter used for GeoTools.## Coding conventions

###Please Note
Libraries or third party software that have costs associated with it will not be allowed in the application.

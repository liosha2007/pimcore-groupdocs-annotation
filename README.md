# Groupdocs Annotation

GroupDocs Annotation plugin for PimCore CMS

With GroupDocs Annotation plugin for PimCore CMS you can easily [annotate on PDF's](http://groupdocs.com/apps/annotation), Word documents, Excel documents, Powerpoint documents and more with the GroupDocs Annotation tool, directly from within your PimCore CMS powered website.

### Plugin Manual Installation Instructions:

1. Copy plugin files from zip archive to '/path-to-installed-pimcore/plugins/' directory.
2. Login to pimcore as admin
3. Go to "Extras"=>"Extensions"=>"Manage Extensions"
4. Click button "Enamble/Disable" and "Install/Unistall"

### Installation from PimCore CMS:

1. Login to pimcore as admin
2. Go to "Extras"=>"Extensions"=>"Download Extensions"
3. Find GroupDoca Annotation plugin and click "Download" button
3. Go to "Extras"=>"Extensions"=>"Manage Extensions"
4. Click button "Enamble/Disable" and "Install/Unistall"

### GroupDocs Annotation plugin using:


For use plugin add code to your view:
```php
<?php $groupDocs = new GroupDocsAnnotation_GroupDocs(); ?>
<?php echo $groupDocs->renderFrame(); ?>
```

Also you can override default params like:
```php
<?php $groupDocs1 = new GroupDocsAnnotation_GroupDocs(array( 'fileId' => '123', 'frameborder' => '1', 'width' => '680', 'height' => '900' )); ?>
<?php echo $groupDocs1->renderFrame(); ?>
```

How to get [Document ID (GUID)](http://groupdocs.com/docs/pages/viewpage.action?pageId=1409575)

###[Sign, Manage, Annotate, Assemble, Compare and Convert Documents with GroupDocs](http://groupdocs.com)
1. [Sign documents online with GroupDocs Signature](http://groupdocs.com/apps/signature)
2. [PDF, Word and Image Annotation with GroupDocs Annotation](http://groupdocs.com/apps/annotation)
3. [Online DOC, DOCX, PPT Document Comparison with GroupDocs Comparison](http://groupdocs.com/apps/comparison)
4. [Online Document Management with GroupDocs Dashboard](http://groupdocs.com/apps/dashboard)
5. [Doc to PDF, Doc to Docx, PPT to PDF, and other Document Conversions with GroupDocs Viewer](http://groupdocs.com/apps/viewer)
6. [Online Document Automation with GroupDocs Assembly](http://groupdocs.com/apps/assembly)

###Created by [GroupDocs Marketplace Team]( http://groupdocs.com/marketplace/ ).
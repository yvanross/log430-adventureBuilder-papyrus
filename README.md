# papyrus-AdventureBuilder

UML modeling using papyrus UML for https://wiki.sei.cmu.edu/confluence/pages/viewpage.action?pageId=146280205

System configuration
Use exactly the same configuration otherwise something will not work.

Install eclipse 2019-06
https://www.eclipse.org/downloads/packages/release/2019-06/r

If you have multiple version of java installed, you could specify which one you want to use for this version of eclipse.
   * Update eclipse.app/Contents/Info.plist to specify your version of java.  I am currently using java jdk16 and it work fine

Install Sysml 1.4 if you want to manage requirement 
	http://download.eclipse.org/modeling/mdt/papyrus/components/sysml14

Install papyrus 4.4 using eclipse help install new software with this url:
	https://download.eclipse.org/modeling/mdt/papyrus/updates/releases/2019-06/

Finally install Gendoc for document generation
	https://download.eclipse.org/gendoc/updates/releases/0.7.2/2019-09/
	
	
Try to generate documentation
Right click on template/adventureBuilder.docx
select Generate documentation using Gendoc
Look in generated directory for your report.

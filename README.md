Sharepoint URLs direct hit on browser

(SharePoint 2013, 2016 you might want to add "15", "16" respectively after "/_layouts/" but if you don't SharePoint will take care of that for you) .. Also some of these are turned off on Office 365 SharePoint online.


1. Site collection level recycle bin:

  /_layouts/15/AdminRecycleBin.aspx

 

2.Site level recycle bin (Added by Steve Stewart):

  /_layouts/RecycleBin.aspx

 

3.Recreate default site sp groups (Added by Neal Bongers):

  _layouts/15/permsetup.aspx

 

4.Load document tab initial (Added by Dominik Gempeler)

  ?InitialTabId=Ribbon.Document

 

5.Delete user from Site collection (on-premises) (Added by SamDavid):

  /_layouts/15/people.aspx?MembershipGroupId=0

 

6.Display list in grid view. 'True' is case sensitive (Added by Antoine L.):

?ShowInGrid=True

 

7.Quick Launch settings page (Added by Ishani M.):

  /_layouts/quiklnch.aspx

 

8.Navigation Settings page (Added by Abdur Raheem):

/_layouts/15/AreaNavigationSettings.aspx

 

9.Sandboxed Solution Gallery:

  /_catalogs/solutions/Forms/AllItems.aspx

 

10.Workflow history hidden list:

  /lists/Workflow History

 

11.Filter toolbar for Lists and libraries (Added by Asimaili):

  ?Filter=1

12.Site usage page (Added by @Dnyag):

  /_layouts/usage.aspx

13.Site content and structure  page (Added by @Dnyag):

    /_layouts/sitemanager.aspx


14.Site settings page (Added by Aowworld):

    /_layouts/settings.aspx

 
15.View all site content page (Site content) (Added by Aowworld):

    /_layouts/viewlsts.aspx

 
16.Manage site collection features - CASE SENSITIVE -  (Added by Vardhaman):

    /_layouts/ManageFeatures.aspx?Scope=Site

 

17.Manage site features (Added by Vardhaman):

    /_layouts/ManageFeatures.aspx

 

18. Get the version of the SharePoint server (Patch level) (Added by: John Liu):

    /_vti_pvt/Service.cnf

 

19.Web Part Maintenance Page (Added by: Ricky):

    ?Contents=1

 

20.Show Page in Dialog View (Added by:Ricky):

    ?isdlg=1


21.Application page for registering SharePoint apps

    /_layouts/15/appregnew.aspx


22.Save Site as a template

    /_layouts/savetmpl.aspx

 

23.Sign in as a different user

    /_layouts/closeConnection.aspx?loginasanotheruser=true

 

24.Enable SharePoint designer

    /_layouts/SharePointDesignerSettings.aspx

 

Welcome Page (Default page settings)

    /_layouts/AreaWelcomePage.aspx

 

25.Change Site Master Page

    /_layouts/ChangeSiteMasterPage.aspx

 

26.Page Layouts and Site Templates

    /_Layouts/AreaTemplateSettings.aspx

 

27.Master Pages library

      /_catalogs/masterpage/Forms/AllItems.aspx

 

28.Quick Deploy List

    Quick%20Deploy%20Items/AllItems.aspx
 

29.Open Page in Edit Mode

    ?ToolPaneView=2

 

30.Taxonomy Hidden List (MMS)

  Lists/TaxonomyHiddenList/AllItems.aspx

 

31.User Information List:

     _catalogs/users

    _catalogs/users/simple.aspx

 

32Force displaying the user profile in the site
collection:

      /_layouts/userdisp.aspx?id={UserID}&Force=True

 

33.Site hierarchy page (lists of sub sites) - (Added by community contributions)

    /_layouts/vsubwebs.aspx

    /_layouts/1033/vsubwebs.aspx

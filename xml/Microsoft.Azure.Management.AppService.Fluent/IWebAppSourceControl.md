<Type Name="IWebAppSourceControl" FullName="Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl">
  <TypeSignature Language="C#" Value="public interface IWebAppSourceControl : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppBase&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteSourceControlInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppBase&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWebAppSourceControl implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IWebAppBase&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteSourceControlInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IWebAppBase&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWebAppSourceControl&#xA;Implements IBeta, IChildResource(Of IWebAppBase), IHasInner(Of SiteSourceControlInner), IHasParent(Of IWebAppBase)" />
  <TypeSignature Language="F#" Value="type IWebAppSourceControl = interface&#xA;    interface IBeta&#xA;    interface IHasInner&lt;SiteSourceControlInner&gt;&#xA;    interface IChildResource&lt;IWebAppBase&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IWebAppBase&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppBase&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteSourceControlInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppBase&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="914cb-101">Eine unveränderliche Darstellung einer Web-app Quelle Konfiguration in einer Web-app.</span><span class="sxs-lookup"><span data-stu-id="914cb-101">An immutable representation of a web app source control configuration in a web app.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="914cb-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="914cb-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Branch">
      <MemberSignature Language="C#" Value="public string Branch { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Branch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl.Branch" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Branch As String" />
      <MemberSignature Language="F#" Value="member this.Branch : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl.Branch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="914cb-103">Ruft den Namen der Branch für die Bereitstellung ab.</span><span class="sxs-lookup"><span data-stu-id="914cb-103">Gets the name of the branch to use for deployment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentRollbackEnabled">
      <MemberSignature Language="C#" Value="public bool DeploymentRollbackEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DeploymentRollbackEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl.DeploymentRollbackEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeploymentRollbackEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.DeploymentRollbackEnabled : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl.DeploymentRollbackEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="914cb-104">Ruft ab, ob Rollback Bereitstellung aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="914cb-104">Gets whether deployment rollback is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsManualIntegration">
      <MemberSignature Language="C#" Value="public bool IsManualIntegration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsManualIntegration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl.IsManualIntegration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsManualIntegration As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsManualIntegration : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl.IsManualIntegration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="914cb-105">Ruft ab, ob manuelle oder fortlaufende Integration führen.</span><span class="sxs-lookup"><span data-stu-id="914cb-105">Gets whether to do manual or continuous integration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RepositoryType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.RepositoryType&gt; RepositoryType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.RepositoryType&gt; RepositoryType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl.RepositoryType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepositoryType As Nullable(Of RepositoryType)" />
      <MemberSignature Language="F#" Value="member this.RepositoryType : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.RepositoryType&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl.RepositoryType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.RepositoryType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="914cb-106">Ruft ab, Mercurial oder Git-Repository-Typ.</span><span class="sxs-lookup"><span data-stu-id="914cb-106">Gets mercurial or Git repository type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RepositoryUrl">
      <MemberSignature Language="C#" Value="public string RepositoryUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RepositoryUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl.RepositoryUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepositoryUrl As String" />
      <MemberSignature Language="F#" Value="member this.RepositoryUrl : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl.RepositoryUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="914cb-107">Ruft den Repository oder die Quelle steuern Url.</span><span class="sxs-lookup"><span data-stu-id="914cb-107">Gets the repository or source control url.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="SiteSourceControl" FullName="Microsoft.Azure.Management.WebSites.Models.SiteSourceControl">
  <TypeSignature Language="C#" Value="public class SiteSourceControl : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SiteSourceControl extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl" />
  <TypeSignature Language="VB.NET" Value="Public Class SiteSourceControl&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type SiteSourceControl = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="8659f-101">Konfigurieren von Datenquellen-Steuerelement für eine app.</span><span class="sxs-lookup"><span data-stu-id="8659f-101">Source control configuration for an app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteSourceControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8659f-102">Initialisiert eine neue Instanz der SiteSourceControl-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8659f-102">Initializes a new instance of the SiteSourceControl class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SiteSourceControl (string id = null, string name = null, string kind = null, string type = null, string repoUrl = null, string branch = null, Nullable&lt;bool&gt; isManualIntegration = null, Nullable&lt;bool&gt; deploymentRollbackEnabled = null, Nullable&lt;bool&gt; isMercurial = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string repoUrl, string branch, valuetype System.Nullable`1&lt;bool&gt; isManualIntegration, valuetype System.Nullable`1&lt;bool&gt; deploymentRollbackEnabled, valuetype System.Nullable`1&lt;bool&gt; isMercurial) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional repoUrl As String = null, Optional branch As String = null, Optional isManualIntegration As Nullable(Of Boolean) = null, Optional deploymentRollbackEnabled As Nullable(Of Boolean) = null, Optional isMercurial As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SiteSourceControl : string * string * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.SiteSourceControl" Usage="new Microsoft.Azure.Management.WebSites.Models.SiteSourceControl (id, name, kind, type, repoUrl, branch, isManualIntegration, deploymentRollbackEnabled, isMercurial)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="repoUrl" Type="System.String" />
        <Parameter Name="branch" Type="System.String" />
        <Parameter Name="isManualIntegration" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="deploymentRollbackEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isMercurial" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="8659f-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="8659f-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="8659f-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="8659f-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="8659f-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8659f-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="8659f-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="8659f-106">Resource type.</span></span></param>
        <param name="repoUrl"><span data-ttu-id="8659f-107">Repository oder Source Control-URL.</span><span class="sxs-lookup"><span data-stu-id="8659f-107">Repository or source control URL.</span></span></param>
        <param name="branch"><span data-ttu-id="8659f-108">Der Name der Branch für die Bereitstellung zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="8659f-108">Name of branch to use for deployment.</span></span></param>
        <param name="isManualIntegration"><span data-ttu-id="8659f-109">&lt;Code&gt;"true"&lt;/code&gt; auf manuelle Integration; beschränken &lt;Code&gt;"false"&lt;/code&gt; fortlaufenden Integration zu aktivieren (die Webhooks in online Repositorys wie GitHub konfiguriert).</span><span class="sxs-lookup"><span data-stu-id="8659f-109">&lt;code&gt;true&lt;/code&gt; to limit to manual integration; &lt;code&gt;false&lt;/code&gt; to enable continuous integration (which configures webhooks into online repos like GitHub).</span></span></param>
        <param name="deploymentRollbackEnabled"><span data-ttu-id="8659f-110">&lt;Code&gt;"true"&lt;/code&gt; So aktivieren Sie die Bereitstellung zurücksetzen; andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="8659f-110">&lt;code&gt;true&lt;/code&gt; to enable deployment rollback; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="isMercurial"><span data-ttu-id="8659f-111">&lt;Code&gt;"true"&lt;/code&gt; für Mercurial-Repository; &lt;Code&gt;"false"&lt;/code&gt; für ein Git-Repository.</span><span class="sxs-lookup"><span data-stu-id="8659f-111">&lt;code&gt;true&lt;/code&gt; for a Mercurial repository; &lt;code&gt;false&lt;/code&gt; for a Git repository.</span></span></param>
        <summary>
            <span data-ttu-id="8659f-112">Initialisiert eine neue Instanz der SiteSourceControl-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8659f-112">Initializes a new instance of the SiteSourceControl class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Branch">
      <MemberSignature Language="C#" Value="public string Branch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Branch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.Branch" />
      <MemberSignature Language="VB.NET" Value="Public Property Branch As String" />
      <MemberSignature Language="F#" Value="member this.Branch : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.Branch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.branch")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8659f-113">Ruft ab, oder legt ihn fest Namen der Branch für die Bereitstellung zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="8659f-113">Gets or sets name of branch to use for deployment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentRollbackEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DeploymentRollbackEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DeploymentRollbackEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.DeploymentRollbackEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentRollbackEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DeploymentRollbackEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.DeploymentRollbackEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deploymentRollbackEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8659f-114">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; So aktivieren Sie die Bereitstellung zurücksetzen; andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="8659f-114">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to enable deployment rollback; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsManualIntegration">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsManualIntegration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsManualIntegration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.IsManualIntegration" />
      <MemberSignature Language="VB.NET" Value="Public Property IsManualIntegration As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsManualIntegration : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.IsManualIntegration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isManualIntegration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8659f-115">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; manuelle Integration; beschränken &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt; fortlaufenden Integration zu aktivieren (die Webhooks in online Repositorys wie GitHub konfiguriert).</span><span class="sxs-lookup"><span data-stu-id="8659f-115">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to limit to manual integration; &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt; to enable continuous integration (which configures webhooks into online repos like GitHub).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsMercurial">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsMercurial { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsMercurial" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.IsMercurial" />
      <MemberSignature Language="VB.NET" Value="Public Property IsMercurial As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsMercurial : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.IsMercurial" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isMercurial")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8659f-116">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; für eine Mercurial-Repository; &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt; für ein Git-Repository.</span><span class="sxs-lookup"><span data-stu-id="8659f-116">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; for a Mercurial repository; &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt; for a Git repository.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RepoUrl">
      <MemberSignature Language="C#" Value="public string RepoUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RepoUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.RepoUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property RepoUrl As String" />
      <MemberSignature Language="F#" Value="member this.RepoUrl : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SiteSourceControl.RepoUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.repoUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8659f-117">Ruft ab, oder legt ihn fest-Repository oder Quelle Steuerelement-URL.</span><span class="sxs-lookup"><span data-stu-id="8659f-117">Gets or sets repository or source control URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
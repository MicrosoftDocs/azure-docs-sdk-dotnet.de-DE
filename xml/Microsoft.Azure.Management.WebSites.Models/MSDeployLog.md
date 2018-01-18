<Type Name="MSDeployLog" FullName="Microsoft.Azure.Management.WebSites.Models.MSDeployLog">
  <TypeSignature Language="C#" Value="public class MSDeployLog : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MSDeployLog extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.MSDeployLog" />
  <TypeSignature Language="VB.NET" Value="Public Class MSDeployLog&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type MSDeployLog = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="ed0ec-101">MSDeploy-Protokoll</span><span class="sxs-lookup"><span data-stu-id="ed0ec-101">MSDeploy log</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MSDeployLog ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MSDeployLog.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ed0ec-102">Initialisiert eine neue Instanz der MSDeployLog-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ed0ec-102">Initializes a new instance of the MSDeployLog class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MSDeployLog (string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry&gt; entries = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry&gt; entries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.MSDeployLog.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional entries As IList(Of MSDeployLogEntry) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.MSDeployLog : string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.MSDeployLog" Usage="new Microsoft.Azure.Management.WebSites.Models.MSDeployLog (id, name, kind, type, entries)" />
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
        <Parameter Name="entries" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="ed0ec-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="ed0ec-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="ed0ec-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="ed0ec-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="ed0ec-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="ed0ec-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="ed0ec-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="ed0ec-106">Resource type.</span></span></param>
        <param name="entries"><span data-ttu-id="ed0ec-107">Liste der Eintrag protokollmeldungen</span><span class="sxs-lookup"><span data-stu-id="ed0ec-107">List of log entry messages</span></span></param>
        <summary>
            <span data-ttu-id="ed0ec-108">Initialisiert eine neue Instanz der MSDeployLog-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ed0ec-108">Initializes a new instance of the MSDeployLog class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Entries">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry&gt; Entries { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry&gt; Entries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.MSDeployLog.Entries" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Entries As IList(Of MSDeployLogEntry)" />
      <MemberSignature Language="F#" Value="member this.Entries : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.MSDeployLog.Entries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.entries")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.MSDeployLogEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ed0ec-109">Ruft die Liste des Protokolls Eintrag Nachrichten</span><span class="sxs-lookup"><span data-stu-id="ed0ec-109">Gets list of log entry messages</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
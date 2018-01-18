<Type Name="SharedAccessAuthorizationRuleResource" FullName="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource">
  <TypeSignature Language="C#" Value="public class SharedAccessAuthorizationRuleResource : Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessAuthorizationRuleResource extends Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessAuthorizationRuleResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SharedAccessAuthorizationRuleResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.NotificationHubs.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="87679-101">Beschreibung des ein Namespace AuthorizationRules.</span><span class="sxs-lookup"><span data-stu-id="87679-101">Description of a Namespace AuthorizationRules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRuleResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="87679-102">Initialisiert eine neue Instanz der SharedAccessAuthorizationRuleResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="87679-102">Initializes a new instance of the SharedAccessAuthorizationRuleResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRuleResource (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.NotificationHubs.Models.Sku sku = null, System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt; rights = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.NotificationHubs.Models.Sku sku, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.NotificationHubs.Models.Sku,System.Collections.Generic.IList{System.Nullable{Microsoft.Azure.Management.NotificationHubs.Models.AccessRights}})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.NotificationHubs.Models.Sku * System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt; -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource (location, id, name, type, tags, sku, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.NotificationHubs.Models.Sku" />
        <Parameter Name="rights" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="87679-103">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="87679-103">Resource location</span></span></param>
        <param name="id"><span data-ttu-id="87679-104">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="87679-104">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="87679-105">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="87679-105">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="87679-106">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="87679-106">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="87679-107">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="87679-107">Resource tags</span></span></param>
        <param name="sku"><span data-ttu-id="87679-108">Die Sku des erstellten namespace</span><span class="sxs-lookup"><span data-stu-id="87679-108">The sku of the created namespace</span></span></param>
        <param name="rights"><span data-ttu-id="87679-109">Die Rechte, die in der Regel zugeordneten.</span><span class="sxs-lookup"><span data-stu-id="87679-109">The rights associated with the rule.</span></span></param>
        <summary>
            <span data-ttu-id="87679-110">Initialisiert eine neue Instanz der SharedAccessAuthorizationRuleResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="87679-110">Initializes a new instance of the SharedAccessAuthorizationRuleResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rights">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt; Rights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt; Rights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource.Rights" />
      <MemberSignature Language="VB.NET" Value="Public Property Rights As IList(Of Nullable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="member this.Rights : System.Collections.Generic.IList&lt;Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleResource.Rights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.rights")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.AccessRights&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87679-111">Ruft ab oder legt die Berechtigungen, die in der Regel zugeordneten.</span><span class="sxs-lookup"><span data-stu-id="87679-111">Gets or sets the rights associated with the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
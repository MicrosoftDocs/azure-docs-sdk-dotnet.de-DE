<Type Name="SharedAccessAuthorizationRuleCreateOrUpdateParameters" FullName="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters">
  <TypeSignature Language="C#" Value="public class SharedAccessAuthorizationRuleCreateOrUpdateParameters : Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessAuthorizationRuleCreateOrUpdateParameters extends Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessAuthorizationRuleCreateOrUpdateParameters&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SharedAccessAuthorizationRuleCreateOrUpdateParameters = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.NotificationHubs.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d89eb-101">Parameter für die CreateOrUpdate Namespace AuthorizationRules bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="d89eb-101">Parameters supplied to the CreateOrUpdate Namespace AuthorizationRules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRuleCreateOrUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d89eb-102">Initialisiert eine neue Instanz der SharedAccessAuthorizationRuleCreateOrUpdateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d89eb-102">Initializes a new instance of the SharedAccessAuthorizationRuleCreateOrUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRuleCreateOrUpdateParameters (string location, Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties properties, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.NotificationHubs.Models.Sku sku = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties properties, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.NotificationHubs.Models.Sku sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters.#ctor(System.String,Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.NotificationHubs.Models.Sku)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters : string * Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.NotificationHubs.Models.Sku -&gt; Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters (location, properties, id, name, type, tags, sku)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.NotificationHubs.Models.Sku" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="d89eb-103">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="d89eb-103">Resource location</span></span></param>
        <param name="properties"><span data-ttu-id="d89eb-104">Eigenschaften der Namespace AuthorizationRules.</span><span class="sxs-lookup"><span data-stu-id="d89eb-104">Properties of the Namespace AuthorizationRules.</span></span></param>
        <param name="id"><span data-ttu-id="d89eb-105">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="d89eb-105">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="d89eb-106">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="d89eb-106">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="d89eb-107">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="d89eb-107">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="d89eb-108">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="d89eb-108">Resource tags</span></span></param>
        <param name="sku"><span data-ttu-id="d89eb-109">Die Sku des erstellten namespace</span><span class="sxs-lookup"><span data-stu-id="d89eb-109">The sku of the created namespace</span></span></param>
        <summary>
            <span data-ttu-id="d89eb-110">Initialisiert eine neue Instanz der SharedAccessAuthorizationRuleCreateOrUpdateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d89eb-110">Initializes a new instance of the SharedAccessAuthorizationRuleCreateOrUpdateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As SharedAccessAuthorizationRuleProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleCreateOrUpdateParameters.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.NotificationHubs.Models.SharedAccessAuthorizationRuleProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d89eb-111">Ruft ab oder legt die Eigenschaften der Namespace AuthorizationRules fest.</span><span class="sxs-lookup"><span data-stu-id="d89eb-111">Gets or sets properties of the Namespace AuthorizationRules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
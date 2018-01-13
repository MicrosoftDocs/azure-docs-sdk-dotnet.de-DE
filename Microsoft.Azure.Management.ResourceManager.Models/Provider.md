<Type Name="Provider" FullName="Microsoft.Azure.Management.ResourceManager.Models.Provider">
  <TypeSignature Language="C#" Value="public class Provider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Provider extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.Provider" />
  <TypeSignature Language="VB.NET" Value="Public Class Provider" />
  <TypeSignature Language="F#" Value="type Provider = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="407c1-101">Informationen zum Ressourcenanbieter.</span><span class="sxs-lookup"><span data-stu-id="407c1-101">Resource provider information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Provider ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.Provider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="407c1-102">Initialisiert eine neue Instanz der Provider-Klasse.</span><span class="sxs-lookup"><span data-stu-id="407c1-102">Initializes a new instance of the Provider class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Provider (string id = null, string namespaceProperty = null, string registrationState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ProviderResourceType&gt; resourceTypes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string namespaceProperty, string registrationState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ProviderResourceType&gt; resourceTypes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.Provider.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Models.ProviderResourceType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional namespaceProperty As String = null, Optional registrationState As String = null, Optional resourceTypes As IList(Of ProviderResourceType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.Provider : string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ProviderResourceType&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.Provider" Usage="new Microsoft.Azure.Management.ResourceManager.Models.Provider (id, namespaceProperty, registrationState, resourceTypes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="namespaceProperty" Type="System.String" />
        <Parameter Name="registrationState" Type="System.String" />
        <Parameter Name="resourceTypes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ProviderResourceType&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="407c1-103">Die Anbieter-ID.</span><span class="sxs-lookup"><span data-stu-id="407c1-103">The provider ID.</span></span></param>
        <param name="namespaceProperty"><span data-ttu-id="407c1-104">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="407c1-104">The namespace of the resource provider.</span></span></param>
        <param name="registrationState"><span data-ttu-id="407c1-105">Der Registrierungsstatus des Anbieters.</span><span class="sxs-lookup"><span data-stu-id="407c1-105">The registration state of the provider.</span></span></param>
        <param name="resourceTypes"><span data-ttu-id="407c1-106">Die Auflistung der anbieterressourcentypen.</span><span class="sxs-lookup"><span data-stu-id="407c1-106">The collection of provider resource types.</span></span></param>
        <summary>
            <span data-ttu-id="407c1-107">Initialisiert eine neue Instanz der Provider-Klasse.</span><span class="sxs-lookup"><span data-stu-id="407c1-107">Initializes a new instance of the Provider class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Provider.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.Provider.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="407c1-108">Ruft die Anbieter-ID.</span><span class="sxs-lookup"><span data-stu-id="407c1-108">Gets the provider ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceProperty">
      <MemberSignature Language="C#" Value="public string NamespaceProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NamespaceProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Provider.NamespaceProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property NamespaceProperty As String" />
      <MemberSignature Language="F#" Value="member this.NamespaceProperty : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.Provider.NamespaceProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="namespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="407c1-109">Ruft ab oder legt den Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="407c1-109">Gets or sets the namespace of the resource provider.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationState">
      <MemberSignature Language="C#" Value="public string RegistrationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegistrationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Provider.RegistrationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegistrationState As String" />
      <MemberSignature Language="F#" Value="member this.RegistrationState : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.Provider.RegistrationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="registrationState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="407c1-110">Ruft den Registrierungsstatus des Anbieters ab.</span><span class="sxs-lookup"><span data-stu-id="407c1-110">Gets the registration state of the provider.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ProviderResourceType&gt; ResourceTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ProviderResourceType&gt; ResourceTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.Provider.ResourceTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceTypes As IList(Of ProviderResourceType)" />
      <MemberSignature Language="F#" Value="member this.ResourceTypes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ProviderResourceType&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Models.Provider.ResourceTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceTypes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Models.ProviderResourceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="407c1-111">Ruft die Auflistung der anbieterressourcentypen ab.</span><span class="sxs-lookup"><span data-stu-id="407c1-111">Gets the collection of provider resource types.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
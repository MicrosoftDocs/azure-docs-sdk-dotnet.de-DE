<Type Name="DeletedVault" FullName="Microsoft.Azure.Management.KeyVault.Models.DeletedVault">
  <TypeSignature Language="C#" Value="public class DeletedVault" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeletedVault extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Models.DeletedVault" />
  <TypeSignature Language="VB.NET" Value="Public Class DeletedVault" />
  <TypeSignature Language="F#" Value="type DeletedVault = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="14c0e-101">Gelöschte tresorinformationen mit nähere Einzelheiten.</span><span class="sxs-lookup"><span data-stu-id="14c0e-101">Deleted vault information with extended details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedVault ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.DeletedVault.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="14c0e-102">Initialisiert eine neue Instanz der DeletedVault-Klasse.</span><span class="sxs-lookup"><span data-stu-id="14c0e-102">Initializes a new instance of the DeletedVault class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedVault (string id = null, string name = null, string type = null, Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.DeletedVault.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional properties As DeletedVaultProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Models.DeletedVault : string * string * string * Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties -&gt; Microsoft.Azure.Management.KeyVault.Models.DeletedVault" Usage="new Microsoft.Azure.Management.KeyVault.Models.DeletedVault (id, name, type, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="14c0e-103">Die Ressourcen-ID für die gelöschten den schlüsseltresor verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="14c0e-103">The resource ID for the deleted key vault.</span></span></param>
        <param name="name"><span data-ttu-id="14c0e-104">Der Name des schlüsseltresors.</span><span class="sxs-lookup"><span data-stu-id="14c0e-104">The name of the key vault.</span></span></param>
        <param name="type"><span data-ttu-id="14c0e-105">Der Ressourcentyp des schlüsseltresors.</span><span class="sxs-lookup"><span data-stu-id="14c0e-105">The resource type of the key vault.</span></span></param>
        <param name="properties"><span data-ttu-id="14c0e-106">Eigenschaften des Tresors</span><span class="sxs-lookup"><span data-stu-id="14c0e-106">Properties of the vault</span></span></param>
        <summary>
            <span data-ttu-id="14c0e-107">Initialisiert eine neue Instanz der DeletedVault-Klasse.</span><span class="sxs-lookup"><span data-stu-id="14c0e-107">Initializes a new instance of the DeletedVault class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="14c0e-108">Ruft die Ressourcen-ID für den gelöschten schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="14c0e-108">Gets the resource ID for the deleted key vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14c0e-109">Ruft den Namen des schlüsseltresors.</span><span class="sxs-lookup"><span data-stu-id="14c0e-109">Gets the name of the key vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As DeletedVaultProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Models.DeletedVaultProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14c0e-110">Ruft ab oder legt die Eigenschaften des Tresors</span><span class="sxs-lookup"><span data-stu-id="14c0e-110">Gets or sets properties of the vault</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string" Usage="Microsoft.Azure.Management.KeyVault.Models.DeletedVault.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="14c0e-111">Ruft den Ressourcentyp des schlüsseltresors ab.</span><span class="sxs-lookup"><span data-stu-id="14c0e-111">Gets the resource type of the key vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
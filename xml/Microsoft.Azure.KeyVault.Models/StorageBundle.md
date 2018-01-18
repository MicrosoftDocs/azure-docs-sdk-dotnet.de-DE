<Type Name="StorageBundle" FullName="Microsoft.Azure.KeyVault.Models.StorageBundle">
  <TypeSignature Language="C#" Value="public class StorageBundle" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageBundle extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.StorageBundle" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageBundle" />
  <TypeSignature Language="F#" Value="type StorageBundle = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8a2bb-101">Ein Speicher-Konto-Paket besteht aus schlüsseltresor speicherkontodetails sowie seiner Attribute.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-101">A Storage account bundle consists of key vault storage account details plus its attributes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageBundle ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.StorageBundle.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8a2bb-102">Initialisiert eine neue Instanz der StorageBundle-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-102">Initializes a new instance of the StorageBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageBundle (string id = null, string resourceId = null, string activeKeyName = null, Nullable&lt;bool&gt; autoRegenerateKey = null, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string resourceId, string activeKeyName, valuetype System.Nullable`1&lt;bool&gt; autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.StorageBundle.#ctor(System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional resourceId As String = null, Optional activeKeyName As String = null, Optional autoRegenerateKey As Nullable(Of Boolean) = null, Optional regenerationPeriod As String = null, Optional attributes As StorageAccountAttributes = null, Optional tags As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.StorageBundle : string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.KeyVault.Models.StorageBundle" Usage="new Microsoft.Azure.KeyVault.Models.StorageBundle (id, resourceId, activeKeyName, autoRegenerateKey, regenerationPeriod, attributes, tags)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="8a2bb-103">Der Speicher-Konto-Id an.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-103">The storage account id.</span></span></param>
        <param name="resourceId"><span data-ttu-id="8a2bb-104">Die Ressourcen-Id Storage-Konto.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-104">The storage account resource id.</span></span></param>
        <param name="activeKeyName"><span data-ttu-id="8a2bb-105">Der aktuellen aktiven Schlüssel speicherkontoname.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-105">The current active storage account key name.</span></span></param>
        <param name="autoRegenerateKey"><span data-ttu-id="8a2bb-106">Gibt an, ob Keyvault das Speicherkonto für den Benutzer verwaltet werden sollen.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-106">whether keyvault should manage the storage account for the user.</span></span></param>
        <param name="regenerationPeriod"><span data-ttu-id="8a2bb-107">Die schlüsselneugenerierung Dauer im ISO 8601-Format angegeben.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-107">The key regeneration time duration specified in ISO-8601 format.</span></span></param>
        <param name="attributes"><span data-ttu-id="8a2bb-108">Die Attribute für den Speicher-Konto.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-108">The storage account attributes.</span></span></param>
        <param name="tags"><span data-ttu-id="8a2bb-109">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren</span><span class="sxs-lookup"><span data-stu-id="8a2bb-109">Application specific metadata in the form of key-value pairs</span></span></param>
        <summary>
            <span data-ttu-id="8a2bb-110">Initialisiert eine neue Instanz der StorageBundle-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-110">Initializes a new instance of the StorageBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveKeyName">
      <MemberSignature Language="C#" Value="public string ActiveKeyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActiveKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageBundle.ActiveKeyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActiveKeyName As String" />
      <MemberSignature Language="F#" Value="member this.ActiveKeyName : string" Usage="Microsoft.Azure.KeyVault.Models.StorageBundle.ActiveKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="activeKeyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a2bb-111">Ruft die aktuelle aktive Schlüssel den Namen des Speicherkontos ab.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-111">Gets the current active storage account key name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Attributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.StorageAccountAttributes Attributes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes Attributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageBundle.Attributes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Attributes As StorageAccountAttributes" />
      <MemberSignature Language="F#" Value="member this.Attributes : Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" Usage="Microsoft.Azure.KeyVault.Models.StorageBundle.Attributes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="attributes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Models.StorageAccountAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a2bb-112">Ruft die Kontoattribute Speicher ab.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-112">Gets the storage account attributes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoRegenerateKey">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AutoRegenerateKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AutoRegenerateKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageBundle.AutoRegenerateKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoRegenerateKey As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AutoRegenerateKey : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.KeyVault.Models.StorageBundle.AutoRegenerateKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="autoRegenerateKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a2bb-113">Ruft ab, ob Keyvault das Speicherkonto für den Benutzer verwalten soll.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-113">Gets whether keyvault should manage the storage account for the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageBundle.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.KeyVault.Models.StorageBundle.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
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
            <span data-ttu-id="8a2bb-114">Ruft die Speicher-Konto-Id ab.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-114">Gets the storage account id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerationPeriod">
      <MemberSignature Language="C#" Value="public string RegenerationPeriod { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegenerationPeriod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageBundle.RegenerationPeriod" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegenerationPeriod As String" />
      <MemberSignature Language="F#" Value="member this.RegenerationPeriod : string" Usage="Microsoft.Azure.KeyVault.Models.StorageBundle.RegenerationPeriod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="regenerationPeriod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a2bb-115">Ruft die schlüsselneugenerierung Dauer im ISO 8601-Format angegeben.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-115">Gets the key regeneration time duration specified in ISO-8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageBundle.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string" Usage="Microsoft.Azure.KeyVault.Models.StorageBundle.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a2bb-116">Ruft die Speicher-Konto-Ressourcen-Id ab.</span><span class="sxs-lookup"><span data-stu-id="8a2bb-116">Gets the storage account resource id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.StorageBundle.Tags" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.KeyVault.Models.StorageBundle.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a2bb-117">Ruft die Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren ab</span><span class="sxs-lookup"><span data-stu-id="8a2bb-117">Gets application specific metadata in the form of key-value pairs</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
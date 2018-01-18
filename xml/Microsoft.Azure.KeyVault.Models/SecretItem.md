<Type Name="SecretItem" FullName="Microsoft.Azure.KeyVault.Models.SecretItem">
  <TypeSignature Language="C#" Value="public class SecretItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecretItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.SecretItem" />
  <TypeSignature Language="VB.NET" Value="Public Class SecretItem" />
  <TypeSignature Language="F#" Value="type SecretItem = class" />
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
            <span data-ttu-id="79d03-101">Das für den geheimen-Element, für den geheimen Metadaten enthält.</span><span class="sxs-lookup"><span data-stu-id="79d03-101">The secret item containing secret metadata.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecretItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SecretItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="79d03-102">Initialisiert eine neue Instanz der SecretItem-Klasse.</span><span class="sxs-lookup"><span data-stu-id="79d03-102">Initializes a new instance of the SecretItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecretItem (string id = null, Microsoft.Azure.KeyVault.Models.SecretAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string contentType = null, Nullable&lt;bool&gt; managed = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.KeyVault.Models.SecretAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string contentType, valuetype System.Nullable`1&lt;bool&gt; managed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SecretItem.#ctor(System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional attributes As SecretAttributes = null, Optional tags As IDictionary(Of String, String) = null, Optional contentType As String = null, Optional managed As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.SecretItem : string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.KeyVault.Models.SecretItem" Usage="new Microsoft.Azure.KeyVault.Models.SecretItem (id, attributes, tags, contentType, managed)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="managed" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="79d03-103">Geheime Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="79d03-103">Secret identifier.</span></span></param>
        <param name="attributes"><span data-ttu-id="79d03-104">Die Attribute für den geheimen Management.</span><span class="sxs-lookup"><span data-stu-id="79d03-104">The secret management attributes.</span></span></param>
        <param name="tags"><span data-ttu-id="79d03-105">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="79d03-105">Application specific metadata in the form of key-value pairs.</span></span></param>
        <param name="contentType"><span data-ttu-id="79d03-106">Typ des Werts für den geheimen z. B. eines Kennworts.</span><span class="sxs-lookup"><span data-stu-id="79d03-106">Type of the secret value such as a password.</span></span></param>
        <param name="managed"><span data-ttu-id="79d03-107">"True", wenn der geheime Lebensdauer von schlüsseltresor verwaltet wird.</span><span class="sxs-lookup"><span data-stu-id="79d03-107">True if the secret's lifetime is managed by key vault.</span></span> <span data-ttu-id="79d03-108">Ist dies ein Schlüssel sichern wird ein Zertifikat, klicken Sie dann verwalteten "true" sein.</span><span class="sxs-lookup"><span data-stu-id="79d03-108">If this is a key backing a certificate, then managed will be true.</span></span></param>
        <summary>
            <span data-ttu-id="79d03-109">Initialisiert eine neue Instanz der SecretItem-Klasse.</span><span class="sxs-lookup"><span data-stu-id="79d03-109">Initializes a new instance of the SecretItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Attributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.SecretAttributes Attributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.SecretAttributes Attributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretItem.Attributes" />
      <MemberSignature Language="VB.NET" Value="Public Property Attributes As SecretAttributes" />
      <MemberSignature Language="F#" Value="member this.Attributes : Microsoft.Azure.KeyVault.Models.SecretAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.SecretItem.Attributes" />
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
        <ReturnType>Microsoft.Azure.KeyVault.Models.SecretAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79d03-110">Ruft ab oder legt die Attribute für den geheimen Management.</span><span class="sxs-lookup"><span data-stu-id="79d03-110">Gets or sets the secret management attributes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretItem.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.SecretItem.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="contentType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79d03-111">Ruft ab oder legt ihn fest der geheimer Wert z. B. eines Kennworts.</span><span class="sxs-lookup"><span data-stu-id="79d03-111">Gets or sets type of the secret value such as a password.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretItem.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.SecretItem.Id" />
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
            <span data-ttu-id="79d03-112">Ruft ab, oder legt ihn fest geheimen Schlüsselbezeichner.</span><span class="sxs-lookup"><span data-stu-id="79d03-112">Gets or sets secret identifier.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.SecretIdentifier Identifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.SecretIdentifier Identifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretItem.Identifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Identifier As SecretIdentifier" />
      <MemberSignature Language="F#" Value="member this.Identifier : Microsoft.Azure.KeyVault.SecretIdentifier" Usage="Microsoft.Azure.KeyVault.Models.SecretItem.Identifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.SecretIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79d03-113">Der Bezeichner für die geheimes Schlüsselobjekt</span><span class="sxs-lookup"><span data-stu-id="79d03-113">The identifier for secret object</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Managed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Managed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Managed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretItem.Managed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Managed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Managed : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.KeyVault.Models.SecretItem.Managed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="managed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="79d03-114">Ruft "true", wenn der geheime Lebensdauer von schlüsseltresor verwaltet wird.</span><span class="sxs-lookup"><span data-stu-id="79d03-114">Gets true if the secret's lifetime is managed by key vault.</span></span> <span data-ttu-id="79d03-115">Ist dies ein Schlüssel sichern wird ein Zertifikat, klicken Sie dann verwalteten "true" sein.</span><span class="sxs-lookup"><span data-stu-id="79d03-115">If this is a key backing a certificate, then managed will be true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretItem.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.SecretItem.Tags" />
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
            <span data-ttu-id="79d03-116">Ruft ab oder legt Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="79d03-116">Gets or sets application specific metadata in the form of key-value pairs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
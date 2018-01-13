<Type Name="KeyBundle" FullName="Microsoft.Azure.KeyVault.Models.KeyBundle">
  <TypeSignature Language="C#" Value="public class KeyBundle" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyBundle extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.KeyBundle" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyBundle" />
  <TypeSignature Language="F#" Value="type KeyBundle = class" />
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
            <span data-ttu-id="a7c51-101">Eine KeyBundle, bestehend aus einem WebKey sowie seiner Attribute.</span><span class="sxs-lookup"><span data-stu-id="a7c51-101">A KeyBundle consisting of a WebKey plus its attributes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyBundle ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyBundle.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a7c51-102">Initialisiert eine neue Instanz der KeyBundle-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a7c51-102">Initializes a new instance of the KeyBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyBundle (Microsoft.Azure.KeyVault.WebKey.JsonWebKey key = null, Microsoft.Azure.KeyVault.Models.KeyAttributes attributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;bool&gt; managed = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, class Microsoft.Azure.KeyVault.Models.KeyAttributes attributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;bool&gt; managed) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.KeyBundle.#ctor(Microsoft.Azure.KeyVault.WebKey.JsonWebKey,Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional key As JsonWebKey = null, Optional attributes As KeyAttributes = null, Optional tags As IDictionary(Of String, String) = null, Optional managed As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.KeyBundle : Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.KeyVault.Models.KeyBundle" Usage="new Microsoft.Azure.KeyVault.Models.KeyBundle (key, attributes, tags, managed)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="managed" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="a7c51-103">Das Json Web Key.</span><span class="sxs-lookup"><span data-stu-id="a7c51-103">The Json web key.</span></span></param>
        <param name="attributes"><span data-ttu-id="a7c51-104">Die schlüsselverwaltung-Attribute.</span><span class="sxs-lookup"><span data-stu-id="a7c51-104">The key management attributes.</span></span></param>
        <param name="tags"><span data-ttu-id="a7c51-105">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="a7c51-105">Application specific metadata in the form of key-value pairs.</span></span></param>
        <param name="managed"><span data-ttu-id="a7c51-106">"True", wenn der Schlüssel Lebensdauer von schlüsseltresor verwaltet wird.</span><span class="sxs-lookup"><span data-stu-id="a7c51-106">True if the key's lifetime is managed by key vault.</span></span> <span data-ttu-id="a7c51-107">Ist dies ein Schlüssel sichern wird ein Zertifikat, klicken Sie dann verwalteten "true" sein.</span><span class="sxs-lookup"><span data-stu-id="a7c51-107">If this is a key backing a certificate, then managed will be true.</span></span></param>
        <summary>
            <span data-ttu-id="a7c51-108">Initialisiert eine neue Instanz der KeyBundle-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a7c51-108">Initializes a new instance of the KeyBundle class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Attributes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Models.KeyAttributes Attributes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Models.KeyAttributes Attributes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyBundle.Attributes" />
      <MemberSignature Language="VB.NET" Value="Public Property Attributes As KeyAttributes" />
      <MemberSignature Language="F#" Value="member this.Attributes : Microsoft.Azure.KeyVault.Models.KeyAttributes with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyBundle.Attributes" />
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
        <ReturnType>Microsoft.Azure.KeyVault.Models.KeyAttributes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7c51-109">Ruft ab oder legt die Attribute für die schlüsselverwaltung.</span><span class="sxs-lookup"><span data-stu-id="a7c51-109">Gets or sets the key management attributes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.WebKey.JsonWebKey Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.WebKey.JsonWebKey Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyBundle.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As JsonWebKey" />
      <MemberSignature Language="F#" Value="member this.Key : Microsoft.Azure.KeyVault.WebKey.JsonWebKey with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyBundle.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.WebKey.JsonWebKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7c51-110">Ruft ab oder legt das Json Web Key.</span><span class="sxs-lookup"><span data-stu-id="a7c51-110">Gets or sets the Json web key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyIdentifier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.KeyIdentifier KeyIdentifier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.KeyIdentifier KeyIdentifier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyBundle.KeyIdentifier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyIdentifier As KeyIdentifier" />
      <MemberSignature Language="F#" Value="member this.KeyIdentifier : Microsoft.Azure.KeyVault.KeyIdentifier" Usage="Microsoft.Azure.KeyVault.Models.KeyBundle.KeyIdentifier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.KeyIdentifier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a7c51-111">Der Bezeichner für das Schlüsselobjekt</span><span class="sxs-lookup"><span data-stu-id="a7c51-111">The identifier for the key object</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Managed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Managed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Managed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyBundle.Managed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Managed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Managed : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.KeyVault.Models.KeyBundle.Managed" />
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
            <span data-ttu-id="a7c51-112">Ruft "true", wenn der Schlüssel Lebensdauer von schlüsseltresor verwaltet wird.</span><span class="sxs-lookup"><span data-stu-id="a7c51-112">Gets true if the key's lifetime is managed by key vault.</span></span> <span data-ttu-id="a7c51-113">Ist dies ein Schlüssel sichern wird ein Zertifikat, klicken Sie dann verwalteten "true" sein.</span><span class="sxs-lookup"><span data-stu-id="a7c51-113">If this is a key backing a certificate, then managed will be true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.KeyBundle.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.KeyBundle.Tags" />
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
            <span data-ttu-id="a7c51-114">Ruft ab oder legt Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="a7c51-114">Gets or sets application specific metadata in the form of key-value pairs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
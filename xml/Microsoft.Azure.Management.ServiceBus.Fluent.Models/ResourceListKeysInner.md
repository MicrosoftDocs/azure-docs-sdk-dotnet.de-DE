<Type Name="ResourceListKeysInner" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner">
  <TypeSignature Language="C#" Value="public class ResourceListKeysInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceListKeysInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceListKeysInner" />
  <TypeSignature Language="F#" Value="type ResourceListKeysInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="811bc-101">Namespace/Service Bus-Verbindungszeichenfolge</span><span class="sxs-lookup"><span data-stu-id="811bc-101">Namespace/ServiceBus Connection String</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceListKeysInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="811bc-102">Initialisiert eine neue Instanz der ResourceListKeysInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="811bc-102">Initializes a new instance of the ResourceListKeysInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceListKeysInner (string primaryConnectionString = null, string secondaryConnectionString = null, string primaryKey = null, string secondaryKey = null, string keyName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string primaryConnectionString, string secondaryConnectionString, string primaryKey, string secondaryKey, string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional primaryConnectionString As String = null, Optional secondaryConnectionString As String = null, Optional primaryKey As String = null, Optional secondaryKey As String = null, Optional keyName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner : string * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner" Usage="new Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner (primaryConnectionString, secondaryConnectionString, primaryKey, secondaryKey, keyName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="primaryConnectionString" Type="System.String" />
        <Parameter Name="secondaryConnectionString" Type="System.String" />
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="secondaryKey" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="primaryConnectionString"><span data-ttu-id="811bc-103">Primäre Verbindungszeichenfolge für den erstellten Namespace-Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="811bc-103">Primary connection string of the created namespace authorization rule.</span></span></param>
        <param name="secondaryConnectionString"><span data-ttu-id="811bc-104">Sekundäre Verbindungszeichenfolge für den erstellten Namespace-Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="811bc-104">Secondary connection string of the created namespace authorization rule.</span></span></param>
        <param name="primaryKey"><span data-ttu-id="811bc-105">Ein primärer Base64-codierter 256-Bit-Schlüssel zum Signieren und Überprüfen des SAS-Tokens.</span><span class="sxs-lookup"><span data-stu-id="811bc-105">A base64-encoded 256-bit primary key for signing and validating the SAS token.</span></span></param>
        <param name="secondaryKey"><span data-ttu-id="811bc-106">Ein sekundärer Base64-codierter 256-Bit-Schlüssel zum Signieren und Überprüfen des SAS-Tokens.</span><span class="sxs-lookup"><span data-stu-id="811bc-106">A base64-encoded 256-bit secondary key for signing and validating the SAS token.</span></span></param>
        <param name="keyName"><span data-ttu-id="811bc-107">Eine Zeichenfolge, die die Autorisierungsregel beschreibt.</span><span class="sxs-lookup"><span data-stu-id="811bc-107">A string that describes the authorization rule.</span></span></param>
        <summary>
            <span data-ttu-id="811bc-108">Initialisiert eine neue Instanz der ResourceListKeysInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="811bc-108">Initializes a new instance of the ResourceListKeysInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="811bc-109">Ruft ab oder legt eine Zeichenfolge, die die Autorisierungsregel beschreibt.</span><span class="sxs-lookup"><span data-stu-id="811bc-109">Gets or sets a string that describes the authorization rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryConnectionString">
      <MemberSignature Language="C#" Value="public string PrimaryConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner.PrimaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryConnectionString : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner.PrimaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="811bc-110">Ruft ab, oder legt ihn fest primäre Verbindungszeichenfolge für den erstellten Namespace-Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="811bc-110">Gets or sets primary connection string of the created namespace authorization rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryKey">
      <MemberSignature Language="C#" Value="public string PrimaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner.PrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryKey : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner.PrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="811bc-111">Ruft ab oder legt einen base64-codierter 256-Bit-primären Schlüssel zum Signieren und überprüfen das SAS-Token.</span><span class="sxs-lookup"><span data-stu-id="811bc-111">Gets or sets a base64-encoded 256-bit primary key for signing and validating the SAS token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryConnectionString">
      <MemberSignature Language="C#" Value="public string SecondaryConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner.SecondaryConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryConnectionString : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner.SecondaryConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryConnectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="811bc-112">Ruft ab, oder legt ihn fest sekundäre Verbindungszeichenfolge für den erstellten Namespace-Autorisierungsregel.</span><span class="sxs-lookup"><span data-stu-id="811bc-112">Gets or sets secondary connection string of the created namespace authorization rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryKey">
      <MemberSignature Language="C#" Value="public string SecondaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner.SecondaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryKey : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Fluent.Models.ResourceListKeysInner.SecondaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="secondaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="811bc-113">Ruft ab oder legt einen base64-codierter 256-Bit-sekundären Schlüssel zum Signieren und überprüfen das SAS-Token.</span><span class="sxs-lookup"><span data-stu-id="811bc-113">Gets or sets a base64-encoded 256-bit secondary key for signing and validating the SAS token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
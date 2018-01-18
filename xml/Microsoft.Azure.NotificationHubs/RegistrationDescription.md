<Type Name="RegistrationDescription" FullName="Microsoft.Azure.NotificationHubs.RegistrationDescription">
  <TypeSignature Language="C#" Value="public abstract class RegistrationDescription : Microsoft.Azure.NotificationHubs.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RegistrationDescription extends Microsoft.Azure.NotificationHubs.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.RegistrationDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RegistrationDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type RegistrationDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.Messaging.EntityDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.BaiduRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.MpnsTemplateRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.AdmRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.AdmTemplateRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.NokiaXRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.NokiaXTemplateRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.BaiduTemplateRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.GcmTemplateRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.GcmRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.AppleRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.AppleTemplateRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.EmailRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.WindowsRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.WindowsTemplateRegistrationDescription))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.Azure.NotificationHubs.MpnsRegistrationDescription))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="f2a46-101">Stellt eine Beschreibung für die Registrierung.</span><span class="sxs-lookup"><span data-stu-id="f2a46-101">Represents a registration description.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegistrationDescription (Microsoft.Azure.NotificationHubs.RegistrationDescription registration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.NotificationHubs.RegistrationDescription registration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RegistrationDescription.#ctor(Microsoft.Azure.NotificationHubs.RegistrationDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (registration As RegistrationDescription)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.RegistrationDescription : Microsoft.Azure.NotificationHubs.RegistrationDescription -&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription" Usage="new Microsoft.Azure.NotificationHubs.RegistrationDescription registration" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="registration" Type="Microsoft.Azure.NotificationHubs.RegistrationDescription" />
      </Parameters>
      <Docs>
        <param name="registration"><span data-ttu-id="f2a46-102">Die Registrierung.</span><span class="sxs-lookup"><span data-stu-id="f2a46-102">The registration.</span></span></param>
        <summary><span data-ttu-id="f2a46-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.RegistrationDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f2a46-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.RegistrationDescription" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deserialize">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.RegistrationDescription Deserialize (string descriptionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.RegistrationDescription Deserialize(string descriptionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RegistrationDescription.Deserialize(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Deserialize (descriptionString As String) As RegistrationDescription" />
      <MemberSignature Language="F#" Value="static member Deserialize : string -&gt; Microsoft.Azure.NotificationHubs.RegistrationDescription" Usage="Microsoft.Azure.NotificationHubs.RegistrationDescription.Deserialize descriptionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.RegistrationDescription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="descriptionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="descriptionString"><span data-ttu-id="f2a46-104">Die Beschreibung der Registrierung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f2a46-104">The description associated with the registration.</span></span></param>
        <summary><span data-ttu-id="f2a46-105">Extrahiert die Beschreibung für die Registrierung aus den serialisierten Daten.</span><span class="sxs-lookup"><span data-stu-id="f2a46-105">Extracts the registration description from the serialized data.</span></span></summary>
        <returns><span data-ttu-id="f2a46-106">Die Beschreibung der Registrierung.</span><span class="sxs-lookup"><span data-stu-id="f2a46-106">The registration description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RegistrationDescription.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.NotificationHubs.RegistrationDescription.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="ETag", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f2a46-107">Ruft ab oder legt das ETag, die diese Beschreibung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f2a46-107">Gets or sets the ETag associated with this description.</span></span></summary>
        <value><span data-ttu-id="f2a46-108">Das ETag diese Beschreibung zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="f2a46-108">The ETag associated with this description.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RegistrationDescription.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.NotificationHubs.RegistrationDescription.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="ExpirationTime", Order=1002)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f2a46-109">Ruft ab oder legt die Ablaufzeit der Registrierung.</span><span class="sxs-lookup"><span data-stu-id="f2a46-109">Gets or sets the expiration time of the registration.</span></span></summary>
        <value><span data-ttu-id="f2a46-110">Die Ablaufzeit der Registrierung.</span><span class="sxs-lookup"><span data-stu-id="f2a46-110">The expiration time of the registration.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateUrlSafeBase64">
      <MemberSignature Language="C#" Value="protected static string GenerateUrlSafeBase64 (byte[] hash);" />
      <MemberSignature Language="ILAsm" Value=".method familystatic hidebysig string GenerateUrlSafeBase64(unsigned int8[] hash) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RegistrationDescription.GenerateUrlSafeBase64(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Protected Shared Function GenerateUrlSafeBase64 (hash As Byte()) As String" />
      <MemberSignature Language="F#" Value="static member GenerateUrlSafeBase64 : byte[] -&gt; string" Usage="Microsoft.Azure.NotificationHubs.RegistrationDescription.GenerateUrlSafeBase64 hash" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hash" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="hash"> <span data-ttu-id="f2a46-111">Der Hash.</span><span class="sxs-lookup"><span data-stu-id="f2a46-111">The hash.</span></span></param>
        <summary><span data-ttu-id="f2a46-112">Generiert eine URL-sichere Base64.</span><span class="sxs-lookup"><span data-stu-id="f2a46-112">Generates a URL safe Base64.</span></span></summary>
        <returns><span data-ttu-id="f2a46-113">Die generierte URL Base64 sicher.</span><span class="sxs-lookup"><span data-stu-id="f2a46-113">The generated URL safe Base64.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationId">
      <MemberSignature Language="C#" Value="public string RegistrationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegistrationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RegistrationDescription.RegistrationId" />
      <MemberSignature Language="VB.NET" Value="Public Property RegistrationId As String" />
      <MemberSignature Language="F#" Value="member this.RegistrationId : string with get, set" Usage="Microsoft.Azure.NotificationHubs.RegistrationDescription.RegistrationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(IsRequired=false, Name="RegistrationId", Order=1003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f2a46-114">Ruft ab oder legt den Registrierungs-ID.</span><span class="sxs-lookup"><span data-stu-id="f2a46-114">Gets or sets the registration ID.</span></span></summary>
        <value><span data-ttu-id="f2a46-115">Die Registrierungs-ID.</span><span class="sxs-lookup"><span data-stu-id="f2a46-115">The registration ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serialize">
      <MemberSignature Language="C#" Value="public string Serialize ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string Serialize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RegistrationDescription.Serialize" />
      <MemberSignature Language="VB.NET" Value="Public Function Serialize () As String" />
      <MemberSignature Language="F#" Value="member this.Serialize : unit -&gt; string" Usage="registrationDescription.Serialize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary> <span data-ttu-id="f2a46-116">Serialisiert die Beschreibung für die Registrierung.</span><span class="sxs-lookup"><span data-stu-id="f2a46-116">Serializes the registration description.</span></span></summary>
        <returns><span data-ttu-id="f2a46-117">Die Beschreibung des serialisierten Registrierung.</span><span class="sxs-lookup"><span data-stu-id="f2a46-117">The serialized registration description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TagCount">
      <MemberSignature Language="C#" Value="public static int TagCount (string tags);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int32 TagCount(string tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RegistrationDescription.TagCount(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function TagCount (tags As String) As Integer" />
      <MemberSignature Language="F#" Value="static member TagCount : string -&gt; int" Usage="Microsoft.Azure.NotificationHubs.RegistrationDescription.TagCount tags" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tags" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tags"><span data-ttu-id="f2a46-118">Die Tags.</span><span class="sxs-lookup"><span data-stu-id="f2a46-118">The tags.</span></span></param>
        <summary><span data-ttu-id="f2a46-119">Gibt die Gesamtanzahl der Transponder zurück.</span><span class="sxs-lookup"><span data-stu-id="f2a46-119">Returns the total number of tags.</span></span></summary>
        <returns><span data-ttu-id="f2a46-120">Die Gesamtanzahl der Transponder.</span><span class="sxs-lookup"><span data-stu-id="f2a46-120">The total number of tags.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.RegistrationDescription.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.ISet&lt;string&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.RegistrationDescription.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f2a46-121">Ermittelt oder definiert einen Satz von Tags, die Registrierung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f2a46-121">Gets or sets a set of tags associated with the registration.</span></span></summary>
        <value><span data-ttu-id="f2a46-122">Ein Satz von Tags, die Registrierung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f2a46-122">A set of tags associated with the registration.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateTags">
      <MemberSignature Language="C#" Value="public static bool ValidateTags (string tags);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool ValidateTags(string tags) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.RegistrationDescription.ValidateTags(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ValidateTags (tags As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member ValidateTags : string -&gt; bool" Usage="Microsoft.Azure.NotificationHubs.RegistrationDescription.ValidateTags tags" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tags" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tags"><span data-ttu-id="f2a46-123">Die Tags, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="f2a46-123">The tags to validate.</span></span></param>
        <summary><span data-ttu-id="f2a46-124">Überprüft die angegebenen Tags an.</span><span class="sxs-lookup"><span data-stu-id="f2a46-124">Validates the given tags.</span></span></summary>
        <returns><span data-ttu-id="f2a46-125">"true", wenn die Tags überprüft werden; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="f2a46-125">true if the tags are validated; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
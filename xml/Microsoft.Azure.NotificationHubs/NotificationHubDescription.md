<Type Name="NotificationHubDescription" FullName="Microsoft.Azure.NotificationHubs.NotificationHubDescription">
  <TypeSignature Language="C#" Value="public sealed class NotificationHubDescription : Microsoft.Azure.NotificationHubs.Messaging.EntityDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NotificationHubDescription extends Microsoft.Azure.NotificationHubs.Messaging.EntityDescription" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NotificationHubDescription&#xA;Inherits EntityDescription" />
  <TypeSignature Language="F#" Value="type NotificationHubDescription = class&#xA;    inherit EntityDescription&#xA;    interface IResourceDescription" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="NotificationHubDescription", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="be76b-101">Stellt eine Notification Hub-Beschreibung an.</span><span class="sxs-lookup"><span data-stu-id="be76b-101">Represents a notification hub description.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NotificationHubDescription (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubDescription.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (path As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.NotificationHubDescription : string -&gt; Microsoft.Azure.NotificationHubs.NotificationHubDescription" Usage="new Microsoft.Azure.NotificationHubs.NotificationHubDescription path" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="be76b-102">Der Pfad der Beschreibung.</span><span class="sxs-lookup"><span data-stu-id="be76b-102">The path of the description.</span></span></param>
        <summary><span data-ttu-id="be76b-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="be76b-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.NotificationHubDescription" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdmCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.AdmCredential AdmCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.AdmCredential AdmCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.AdmCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property AdmCredential As AdmCredential" />
      <MemberSignature Language="F#" Value="member this.AdmCredential : Microsoft.Azure.NotificationHubs.AdmCredential with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.AdmCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="AdmCredential", Order=1014)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.AdmCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-104">Ruft ab oder legt die administrative Anmeldeinformationen fest.</span><span class="sxs-lookup"><span data-stu-id="be76b-104">Gets or sets the administrative credential.</span></span></summary>
        <value><span data-ttu-id="be76b-105">Die Administratoranmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="be76b-105">The administrative credential.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApnsCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.ApnsCredential ApnsCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.ApnsCredential ApnsCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.ApnsCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property ApnsCredential As ApnsCredential" />
      <MemberSignature Language="F#" Value="member this.ApnsCredential : Microsoft.Azure.NotificationHubs.ApnsCredential with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.ApnsCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="ApnsCredential", Order=1001)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.ApnsCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-106">Ruft ab oder legt die APNs-Anmeldeinformationen fest.</span><span class="sxs-lookup"><span data-stu-id="be76b-106">Gets or sets the APNS credential.</span></span></summary>
        <value><span data-ttu-id="be76b-107">APNs-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="be76b-107">The APNS credential.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules Authorization { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authorization As AuthorizationRules" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.AuthorizationRules</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-108">Ruft die Autorisierungsregeln für diese Beschreibung ab.</span><span class="sxs-lookup"><span data-stu-id="be76b-108">Gets the authorization rules for this description.</span></span></summary>
        <value><span data-ttu-id="be76b-109">Die Autorisierungsregeln für diese Beschreibung.</span><span class="sxs-lookup"><span data-stu-id="be76b-109">The authorization rules for this description.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaiduCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.BaiduCredential BaiduCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.BaiduCredential BaiduCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.BaiduCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property BaiduCredential As BaiduCredential" />
      <MemberSignature Language="F#" Value="member this.BaiduCredential : Microsoft.Azure.NotificationHubs.BaiduCredential with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.BaiduCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="BaiduCredential", Order=1016)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.BaiduCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be76b-110">Ruft ab oder legt die Baidu-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="be76b-110">Gets or sets the Baidu credential.</span></span>
            </summary>
        <value>
            <span data-ttu-id="be76b-111">Die Baidu-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="be76b-111">The Baidu credential.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyApiCalls">
      <MemberSignature Language="C#" Value="public long DailyApiCalls { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DailyApiCalls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyApiCalls" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DailyApiCalls As Long" />
      <MemberSignature Language="F#" Value="member this.DailyApiCalls : int64" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyApiCalls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="DailyApiCalls", Order=1013)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-112">Ruft die tägliche API-Aufrufe für die Benachrichtigung ab.</span><span class="sxs-lookup"><span data-stu-id="be76b-112">Gets the daily API calls for the notification.</span></span></summary>
        <value><span data-ttu-id="be76b-113">Die täglichen API-Aufrufe für die Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="be76b-113">The daily API calls for the notification.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyMaxActiveDevices">
      <MemberSignature Language="C#" Value="public long DailyMaxActiveDevices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DailyMaxActiveDevices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyMaxActiveDevices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DailyMaxActiveDevices As Long" />
      <MemberSignature Language="F#" Value="member this.DailyMaxActiveDevices : int64" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyMaxActiveDevices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="DailyMaxActiveDevices", Order=1008)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-114">Ruft die tägliche maximale aktiver Geräte für die Benachrichtigung ab.</span><span class="sxs-lookup"><span data-stu-id="be76b-114">Gets the daily maximum active devices for notification.</span></span></summary>
        <value><span data-ttu-id="be76b-115">Die tägliche maximale active Geräte für die Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="be76b-115">The daily maximum active devices for notification.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyMaxActiveRegistrations">
      <MemberSignature Language="C#" Value="public long DailyMaxActiveRegistrations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DailyMaxActiveRegistrations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyMaxActiveRegistrations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DailyMaxActiveRegistrations As Long" />
      <MemberSignature Language="F#" Value="member this.DailyMaxActiveRegistrations : int64" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyMaxActiveRegistrations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="DailyMaxActiveRegistrations", Order=1009)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-116">Ruft die tägliche maximale aktiven Registrierungen für die Benachrichtigung ab.</span><span class="sxs-lookup"><span data-stu-id="be76b-116">Gets the daily maximum active registrations for the notification.</span></span></summary>
        <value><span data-ttu-id="be76b-117">Die tägliche maximale aktiven Registrierungen für die Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="be76b-117">The daily maximum active registrations for the notification.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyOperations">
      <MemberSignature Language="C#" Value="public long DailyOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DailyOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DailyOperations As Long" />
      <MemberSignature Language="F#" Value="member this.DailyOperations : int64" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="DailyOperations", Order=1007)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-118">Ruft die täglichen Vorgänge für die Beschreibung ab.</span><span class="sxs-lookup"><span data-stu-id="be76b-118">Gets the daily operations for the description.</span></span></summary>
        <value><span data-ttu-id="be76b-119">Die täglichen Vorgänge für die Beschreibung.</span><span class="sxs-lookup"><span data-stu-id="be76b-119">The daily operations for the description.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyPushes">
      <MemberSignature Language="C#" Value="public long DailyPushes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DailyPushes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyPushes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DailyPushes As Long" />
      <MemberSignature Language="F#" Value="member this.DailyPushes : int64" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DailyPushes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="DailyPushes", Order=1012)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-120">Ruft die tägliche Push-Vorgänge für die Benachrichtigung ab.</span><span class="sxs-lookup"><span data-stu-id="be76b-120">Gets the daily pushes for the notification.</span></span></summary>
        <value><span data-ttu-id="be76b-121">Die täglichen Push-Vorgänge für die Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="be76b-121">The daily pushes for the notification.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultFullSasRuleName">
      <MemberSignature Language="C#" Value="public const string DefaultFullSasRuleName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultFullSasRuleName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DefaultFullSasRuleName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultFullSasRuleName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultFullSasRuleName : string" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DefaultFullSasRuleName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-122">Gibt die vollständige SAS-Regel Standardnamen.</span><span class="sxs-lookup"><span data-stu-id="be76b-122">Specifies the default full SAS rule name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultListenSasRuleName">
      <MemberSignature Language="C#" Value="public const string DefaultListenSasRuleName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultListenSasRuleName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.NotificationHubs.NotificationHubDescription.DefaultListenSasRuleName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultListenSasRuleName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultListenSasRuleName : string" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.DefaultListenSasRuleName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-123">Gibt den Standardnamen Lauschen SAS-Regel an.</span><span class="sxs-lookup"><span data-stu-id="be76b-123">Specifies the default listen SAS rule name.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GcmCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.GcmCredential GcmCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.GcmCredential GcmCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.GcmCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property GcmCredential As GcmCredential" />
      <MemberSignature Language="F#" Value="member this.GcmCredential : Microsoft.Azure.NotificationHubs.GcmCredential with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.GcmCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="GcmCredential", Order=1005)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.GcmCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-124">Ruft ab oder legt die GCM-Anmeldeinformationen fest.</span><span class="sxs-lookup"><span data-stu-id="be76b-124">Gets or sets the GCM credential.</span></span></summary>
        <value><span data-ttu-id="be76b-125">Die GCM-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="be76b-125">The GCM credential.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAnonymousAccessible">
      <MemberSignature Language="C#" Value="public bool IsAnonymousAccessible { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsAnonymousAccessible" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.IsAnonymousAccessible" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsAnonymousAccessible As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsAnonymousAccessible : bool" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.IsAnonymousAccessible" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-126">Ruft einen Wert, der angibt, ob die Beschreibung anonym zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="be76b-126">Gets a value indicating whether the description is anonymously accessible.</span></span></summary>
        <value><span data-ttu-id="be76b-127">"true", wenn die Beschreibung anonym zugegriffen werden kann; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="be76b-127">true if the description is anonymously accessible; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDisabled">
      <MemberSignature Language="C#" Value="public bool IsDisabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDisabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.IsDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDisabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDisabled : bool with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.IsDisabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.IgnoreDataMember</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="be76b-128">Ruft ab oder legt einen Wert, der angibt, ob dieser Notification Hub deaktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="be76b-128">Gets of sets a value indicating if this notification hub is disabled.</span></span> <span data-ttu-id="be76b-129">Wenn <see langword="true" /> alle laufzeitvorgänge (d. h. registrierungsverwaltung und sendet) HTTP-Statuscode 403 zurück <see cref="F:System.Net.HttpStatusCode.Forbidden" />.</span><span class="sxs-lookup"><span data-stu-id="be76b-129">When <see langword="true" /> all runtime operations (i.e. registration management and sends) will return HTTP status code 403 <see cref="F:System.Net.HttpStatusCode.Forbidden" />.</span></span>
            </summary>
        <value>
          <span data-ttu-id="be76b-130"><see langword="true" />Wenn dieser Notification Hub deaktiviert ist. andernfalls <see langword="false" />.</span><span class="sxs-lookup"><span data-stu-id="be76b-130"><see langword="true" /> if this notification hub is disabled; otherwise, <see langword="false" />.</span></span>
            </value>
        <remarks>
            <span data-ttu-id="be76b-131">Mehrinstanzenfähige Anwendungen sind Anwendungen, die auf einer einzelnen mobilen Anwendung für mehrere Parteien (oder Mandanten) Pushbenachrichtigungen an.</span><span class="sxs-lookup"><span data-stu-id="be76b-131">Multi-tenant applications are applications that have to push notifications to a single mobile application on behalf of multiple parties (or tenants).</span></span> <span data-ttu-id="be76b-132">Ein Muster, um dieses Ziel zu erreichen, das was die Benutzerisolation zwischen Mandanten erzielt wird, besteht darin, einen Hub pro Mandant erstellen und Speichern von Anmeldeinformationen auf Namespace-Ebene.</span><span class="sxs-lookup"><span data-stu-id="be76b-132">One pattern to achieve this goal, which achieves user isolation between tenants, is to create one hub per tenant and store application credentials at the namespace level.</span></span> <span data-ttu-id="be76b-133">In diesen Fällen jedoch erforderlich, damit die Anwendung mit mehreren Mandanten, die benachrichtigungs-Hub, der einen bestimmten Mandanten zu deaktivieren, um Missbrauch (entweder die stammenden in dienstverschlechterung für andere Mandanten oder zusätzliche Gebühren für mehrere Mandanten zu verhindern möglicherweise Besitzer der Anwendung).</span><span class="sxs-lookup"><span data-stu-id="be76b-133">In these cases though, it might be required for the multi-tenant application to disable the notification hub of a particular tenant in order to avoid abuse (either resulting in service degradation for other tenants, or in extra charges for the multi-tenant application owner).</span></span>
            </remarks>
        <altmember cref="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.InternalStatus" />
        <altmember cref="T:System.Net.HttpStatusCode" />
      </Docs>
    </Member>
    <Member MemberName="MpnsCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.MpnsCredential MpnsCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.MpnsCredential MpnsCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.MpnsCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property MpnsCredential As MpnsCredential" />
      <MemberSignature Language="F#" Value="member this.MpnsCredential : Microsoft.Azure.NotificationHubs.MpnsCredential with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.MpnsCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="MpnsCredential", Order=1006)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.MpnsCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-134">Ruft ab oder legt die MPNS-Anmeldeinformationen fest.</span><span class="sxs-lookup"><span data-stu-id="be76b-134">Gets or sets the MPNS credential.</span></span> <span data-ttu-id="be76b-135">Eine <see cref="T:Microsoft.Azure.NotificationHubs.MpnsCredential" /> -Instanz mit keine definierten Zertifikat ermöglicht MPNS nicht authentifizierte MPNS-Unterstützung.</span><span class="sxs-lookup"><span data-stu-id="be76b-135">An <see cref="T:Microsoft.Azure.NotificationHubs.MpnsCredential" /> instance with no defined certificate enables MPNS unauthenticated MPNS support.</span></span></summary>
        <value><span data-ttu-id="be76b-136">Der MPNS-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="be76b-136">The MPNS credential.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-137">Ruft ab oder legt den Pfad dieser Beschreibung fest.</span><span class="sxs-lookup"><span data-stu-id="be76b-137">Gets or sets the path of this description.</span></span></summary>
        <value><span data-ttu-id="be76b-138">Der Pfad dieser Beschreibung.</span><span class="sxs-lookup"><span data-stu-id="be76b-138">The path of this description.</span></span></value>
        <remarks>
              <span data-ttu-id="be76b-139">Dies ist ein relativer Pfad zu der <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManager.Address" />.</span><span class="sxs-lookup"><span data-stu-id="be76b-139">This is a relative path to the <see cref="P:Microsoft.Azure.NotificationHubs.NamespaceManager.Address" />.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationTtl">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RegistrationTtl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RegistrationTtl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.RegistrationTtl" />
      <MemberSignature Language="VB.NET" Value="Public Property RegistrationTtl As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RegistrationTtl : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.RegistrationTtl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-140">Ruft ab oder legt die Ablaufzeit für alle Registrierungen in diesem benachrichtigungshub.</span><span class="sxs-lookup"><span data-stu-id="be76b-140">Gets or sets the expiration time of all registrations in this notification hub.</span></span></summary>
        <value><span data-ttu-id="be76b-141">Die Gültigkeitsdauer (TTL) für die Registrierung.</span><span class="sxs-lookup"><span data-stu-id="be76b-141">The registration TTL.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetAccessPasswords">
      <MemberSignature Language="C#" Value="public void SetAccessPasswords (string fullAccessRuleName, string fullAccessPassword, string listenAccessRuleName, string listenAccessPassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetAccessPasswords(string fullAccessRuleName, string fullAccessPassword, string listenAccessRuleName, string listenAccessPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubDescription.SetAccessPasswords(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetAccessPasswords (fullAccessRuleName As String, fullAccessPassword As String, listenAccessRuleName As String, listenAccessPassword As String)" />
      <MemberSignature Language="F#" Value="member this.SetAccessPasswords : string * string * string * string -&gt; unit" Usage="notificationHubDescription.SetAccessPasswords (fullAccessRuleName, fullAccessPassword, listenAccessRuleName, listenAccessPassword)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fullAccessRuleName" Type="System.String" />
        <Parameter Name="fullAccessPassword" Type="System.String" />
        <Parameter Name="listenAccessRuleName" Type="System.String" />
        <Parameter Name="listenAccessPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fullAccessRuleName"><span data-ttu-id="be76b-142">Der Regelname "Vollzugriff".</span><span class="sxs-lookup"><span data-stu-id="be76b-142">The full access rule name.</span></span></param>
        <param name="fullAccessPassword"><span data-ttu-id="be76b-143">Das Kennwort Vollzugriff.</span><span class="sxs-lookup"><span data-stu-id="be76b-143">The full access password.</span></span></param>
        <param name="listenAccessRuleName"><span data-ttu-id="be76b-144">Der Name der Überwachung Zugriff-Regel.</span><span class="sxs-lookup"><span data-stu-id="be76b-144">The listen access rule name.</span></span></param>
        <param name="listenAccessPassword"><span data-ttu-id="be76b-145">Das Zugriffskennwort für die Überwachung.</span><span class="sxs-lookup"><span data-stu-id="be76b-145">The listen access password.</span></span></param>
        <summary><span data-ttu-id="be76b-146">Legt fest, die Kennwörter für den Zugriff.</span><span class="sxs-lookup"><span data-stu-id="be76b-146">Sets the access passwords.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="be76b-147">FullAccessRuleName oder FullAccessPassword oder ListenAccessRuleName oder listenAccessPassword</span><span class="sxs-lookup"><span data-stu-id="be76b-147">fullAccessRuleName or fullAccessPassword or listenAccessRuleName or listenAccessPassword</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SetDefaultAccessPasswords">
      <MemberSignature Language="C#" Value="public void SetDefaultAccessPasswords (string fullAccessPassword, string listenAccessPassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetDefaultAccessPasswords(string fullAccessPassword, string listenAccessPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.NotificationHubDescription.SetDefaultAccessPasswords(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetDefaultAccessPasswords (fullAccessPassword As String, listenAccessPassword As String)" />
      <MemberSignature Language="F#" Value="member this.SetDefaultAccessPasswords : string * string -&gt; unit" Usage="notificationHubDescription.SetDefaultAccessPasswords (fullAccessPassword, listenAccessPassword)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fullAccessPassword" Type="System.String" />
        <Parameter Name="listenAccessPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fullAccessPassword"><span data-ttu-id="be76b-148">Das Kennwort Vollzugriff.</span><span class="sxs-lookup"><span data-stu-id="be76b-148">The full access password.</span></span></param>
        <param name="listenAccessPassword"><span data-ttu-id="be76b-149">Das Zugriffskennwort für die Überwachung.</span><span class="sxs-lookup"><span data-stu-id="be76b-149">The listen access password.</span></span></param>
        <summary><span data-ttu-id="be76b-150">Die Standardeinstellung festgelegt Zugriff Kennwörter.</span><span class="sxs-lookup"><span data-stu-id="be76b-150">Sets the default access passwords.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            <span data-ttu-id="be76b-151">FullAccessPassword oder listenAccessPassword</span><span class="sxs-lookup"><span data-stu-id="be76b-151">fullAccessPassword or listenAccessPassword</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="UserMetadata">
      <MemberSignature Language="C#" Value="public string UserMetadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserMetadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.UserMetadata" />
      <MemberSignature Language="VB.NET" Value="Public Property UserMetadata As String" />
      <MemberSignature Language="F#" Value="member this.UserMetadata : string with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.UserMetadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-152">Abrufen oder Festlegen der dieser Beschreibung zugeordnete Benutzermetadaten.</span><span class="sxs-lookup"><span data-stu-id="be76b-152">Gets or sets the user metadata associated with the description.</span></span></summary>
        <value><span data-ttu-id="be76b-153">Die dieser Beschreibung zugeordnete Benutzermetadaten.</span><span class="sxs-lookup"><span data-stu-id="be76b-153">The user metadata associated with the description.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WnsCredential">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.WnsCredential WnsCredential { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.NotificationHubs.WnsCredential WnsCredential" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.NotificationHubDescription.WnsCredential" />
      <MemberSignature Language="VB.NET" Value="Public Property WnsCredential As WnsCredential" />
      <MemberSignature Language="F#" Value="member this.WnsCredential : Microsoft.Azure.NotificationHubs.WnsCredential with get, set" Usage="Microsoft.Azure.NotificationHubs.NotificationHubDescription.WnsCredential" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.DataMember(EmitDefaultValue=false, IsRequired=false, Name="WnsCredential", Order=1003)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.WnsCredential</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="be76b-154">Ruft ab oder legt die Anmeldeinformationen für WNS.</span><span class="sxs-lookup"><span data-stu-id="be76b-154">Gets or sets the WNS credential.</span></span></summary>
        <value><span data-ttu-id="be76b-155">WNS-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="be76b-155">The WNS credential.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
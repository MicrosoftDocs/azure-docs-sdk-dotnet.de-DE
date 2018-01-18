<Type Name="MobileAppSettingsDictionary" FullName="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary">
  <TypeSignature Language="C#" Value="public class MobileAppSettingsDictionary : System.Collections.Generic.Dictionary&lt;string,string&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MobileAppSettingsDictionary extends System.Collections.Generic.Dictionary`2&lt;string, string&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileAppSettingsDictionary&#xA;Inherits Dictionary(Of String, String)" />
  <TypeSignature Language="F#" Value="type MobileAppSettingsDictionary = class&#xA;    inherit Dictionary&lt;string, string&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">System.String</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="!1">System.String</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Usage", "CA2240:ImplementISerializableCorrectly", Justification="Not intended for serialization")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="fac07-101">Enthält Einstellungen für einen Dienst, z. B. die Verbindungszeichenfolgen, Hostname, Abonnement-ID usw. Die <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> enthält typisierte Eigenschaften für bekannte Einstellungen wie z. B. <see cref="M:HostName" /> und <see cref="M:SubscriptionId" /> sowie <see cref="T:System.Collections.Generic.IDictionary`2" /> Zugriff für alle anderen Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="fac07-101">Contains settings for a service such as the connection strings, host name, subscription ID, etc. The <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> provides typed properties for known settings such as <see cref="M:HostName" /> and <see cref="M:SubscriptionId" /> as well as <see cref="T:System.Collections.Generic.IDictionary`2" /> access for all other settings.</span></span>
            </summary>
    <remarks><span data-ttu-id="fac07-102">Bleiben alle Eigenschaftswerte, legen Sie für eine Instanz nur bestehen für die Lebensdauer des aktuellen <see cref="T:System.AppDomain" />.</span><span class="sxs-lookup"><span data-stu-id="fac07-102">Any property values set on an instance will only stay in effect for the lifetime of the current <see cref="T:System.AppDomain" />.</span></span>
            <span data-ttu-id="fac07-103">Um die Einstellungen in einer persistenten Weise zu ändern, aktualisieren Sie sie mit einem Mechanismus zur Verfügung gestellt, die vom Diensthost.</span><span class="sxs-lookup"><span data-stu-id="fac07-103">To change the settings in a persistent manner, please update them using a mechanism provided by the service host.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileAppSettingsDictionary ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fac07-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fac07-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MobileAppSettingsDictionary (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" Usage="new Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="fac07-105">Ein <see cref="T:System.Runtime.Serialization.SerializationInfo" /> mit Informationen über die <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> initialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="fac07-105">A <see cref="T:System.Runtime.Serialization.SerializationInfo" /> containing information about the <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> to be initialized.</span></span></param>
        <param name="context"><span data-ttu-id="fac07-106">Ein <see cref="T:System.Runtime.Serialization.StreamingContext" /> , der die Quellinformationen Ziel und Kontext eines serialisierten Streams angibt.</span><span class="sxs-lookup"><span data-stu-id="fac07-106">A <see cref="T:System.Runtime.Serialization.StreamingContext" /> that indicates the source destination and context information of a serialized stream.</span></span></param>
        <summary>
            <span data-ttu-id="fac07-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" />-Klasse mit den angegebenen Serialisierungsinformationen und dem angegebenen Streamingkontext.</span><span class="sxs-lookup"><span data-stu-id="fac07-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> class with the specified serialization information and streaming context.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Connections">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Mobile.Server.ConnectionSettings&gt; Connections { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Mobile.Server.ConnectionSettings&gt; Connections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.Connections" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Connections As IDictionary(Of String, ConnectionSettings)" />
      <MemberSignature Language="F#" Value="member this.Connections : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Mobile.Server.ConnectionSettings&gt;" Usage="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.Connections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Mobile.Server.ConnectionSettings&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fac07-108">Ruft den Satz von Verbindungszeichenfolgen für den Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="fac07-108">Gets the set of connection strings for the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public virtual string HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string with get, set" Usage="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fac07-109">Ruft ab oder legt den Hostnamen des Diensts fest.</span><span class="sxs-lookup"><span data-stu-id="fac07-109">Gets or sets the host name of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public string this[string key] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(key As String) As String" />
      <MemberSignature Language="F#" Value="member this.Item(string) : string with get, set" Usage="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="fac07-110">Der Schlüssel des abzurufenden oder festzulegenden Werts.</span><span class="sxs-lookup"><span data-stu-id="fac07-110">The key of the value to get or set.</span></span></param>
        <summary>
            <span data-ttu-id="fac07-111">Ruft den Wert ab, der dem angegebenen Schlüssel zugeordnet ist, oder legt diesen fest.</span><span class="sxs-lookup"><span data-stu-id="fac07-111">Gets or sets the value associated with the specified key.</span></span>
            </summary>
        <value><span data-ttu-id="fac07-112">Der dem angegebenen Schlüssel zugeordnete Wert.</span><span class="sxs-lookup"><span data-stu-id="fac07-112">The value associated with the specified key.</span></span> <span data-ttu-id="fac07-113">Wenn der angegebene Schlüssel nicht gefunden wird, löst ein Get-Vorgang eine <see cref="T:System.Collections.Generic.KeyNotFoundException" /> aus, und durch einen Set-Vorgang wird ein neues Element mit dem angegebenen Schlüssel erstellt.</span><span class="sxs-lookup"><span data-stu-id="fac07-113">If the specified key is not found, a get operation throws a <see cref="T:System.Collections.Generic.KeyNotFoundException" />, and a set operation creates a new element with the specified key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationHubName">
      <MemberSignature Language="C#" Value="public virtual string NotificationHubName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NotificationHubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.NotificationHubName" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property NotificationHubName As String" />
      <MemberSignature Language="F#" Value="member this.NotificationHubName : string with get, set" Usage="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.NotificationHubName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fac07-114">Ruft ab oder legt den Namen des diesem Dienst für die Behandlung von Pushbenachrichtigungen zugeordnete Benachrichtigungs-Hub.</span><span class="sxs-lookup"><span data-stu-id="fac07-114">Gets or sets the name of the Notification Hub associated with this service for handling push notifications.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkipVersionCheck">
      <MemberSignature Language="C#" Value="public virtual bool SkipVersionCheck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool SkipVersionCheck" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.SkipVersionCheck" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property SkipVersionCheck As Boolean" />
      <MemberSignature Language="F#" Value="member this.SkipVersionCheck : bool with get, set" Usage="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.SkipVersionCheck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fac07-115">Ruft ab oder legt einen Wert, der angibt, ob die ZUMO-API-VERSION-Header überprüft für alle Aufrufe an "mobileapp" Controller übersprungen werden.</span><span class="sxs-lookup"><span data-stu-id="fac07-115">Gets or sets a value indicating whether ZUMO-API-VERSION header checks are skipped for all calls to MobileApp controllers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public virtual string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fac07-116">Ruft ab oder legt die "subscriptionId" des Diensts.</span><span class="sxs-lookup"><span data-stu-id="fac07-116">Gets or sets the SubscriptionId of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
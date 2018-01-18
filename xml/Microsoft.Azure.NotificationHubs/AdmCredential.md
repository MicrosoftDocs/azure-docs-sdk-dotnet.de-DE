<Type Name="AdmCredential" FullName="Microsoft.Azure.NotificationHubs.AdmCredential">
  <TypeSignature Language="C#" Value="public class AdmCredential : Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdmCredential extends Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.AdmCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class AdmCredential&#xA;Inherits PnsCredential" />
  <TypeSignature Language="F#" Value="type AdmCredential = class&#xA;    inherit PnsCredential" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.PnsCredential</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="AdmCredential", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary><span data-ttu-id="6a0c1-101">Gibt die Anmeldeinformationen Amazon Device Messaging (ADM).</span><span class="sxs-lookup"><span data-stu-id="6a0c1-101">Specifies the Amazon Device Messaging (ADM) credentials.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdmCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6a0c1-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AdmCredential" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AdmCredential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdmCredential (string clientId, string clientSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string clientSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmCredential.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String, clientSecret As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.AdmCredential : string * string -&gt; Microsoft.Azure.NotificationHubs.AdmCredential" Usage="new Microsoft.Azure.NotificationHubs.AdmCredential (clientId, clientSecret)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="clientSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="6a0c1-103">The client identifier. (Der Clientbezeichner.)</span><span class="sxs-lookup"><span data-stu-id="6a0c1-103">The client identifier.</span></span></param>
        <param name="clientSecret"><span data-ttu-id="6a0c1-104">Die Anmeldeinformationen für den geheimen Tastenkombination.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-104">The credential secret access key.</span></span></param>
        <summary><span data-ttu-id="6a0c1-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.AdmCredential" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.AdmCredential" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthTokenUrl">
      <MemberSignature Language="C#" Value="public string AuthTokenUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AuthTokenUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AdmCredential.AuthTokenUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthTokenUrl As String" />
      <MemberSignature Language="F#" Value="member this.AuthTokenUrl : string with get, set" Usage="Microsoft.Azure.NotificationHubs.AdmCredential.AuthTokenUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6a0c1-106">Ruft ab oder legt die URL des autorisierungstokens fest.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-106">Gets or sets the URL of the authorization token.</span></span></summary>
        <value><span data-ttu-id="6a0c1-107">Die URL der das Autorisierungstoken.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-107">The URL of the authorization token.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AdmCredential.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string with get, set" Usage="Microsoft.Azure.NotificationHubs.AdmCredential.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6a0c1-108">Ruft ab oder legt den Clientbezeichner.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-108">Gets or sets the client identifier.</span></span></summary>
        <value><span data-ttu-id="6a0c1-109">The client identifier. (Der Clientbezeichner.)</span><span class="sxs-lookup"><span data-stu-id="6a0c1-109">The client identifier.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientSecret">
      <MemberSignature Language="C#" Value="public string ClientSecret { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientSecret" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AdmCredential.ClientSecret" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientSecret As String" />
      <MemberSignature Language="F#" Value="member this.ClientSecret : string with get, set" Usage="Microsoft.Azure.NotificationHubs.AdmCredential.ClientSecret" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6a0c1-110">Ruft ab oder legt den Anmeldeinformationen Zugriff für den geheimen Schlüssel fest.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-110">Gets or sets the credential secret access key.</span></span></summary>
        <value><span data-ttu-id="6a0c1-111">Die Anmeldeinformationen für den geheimen Tastenkombination.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-111">The credential secret access key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmCredential.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (other As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="admCredential.Equals other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="other"><span data-ttu-id="6a0c1-112">Das zu vergleichende Objekt.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-112">The object to compare.</span></span></param>
        <summary><span data-ttu-id="6a0c1-113">Gibt an, ob die Anmeldeinformationen mit dem angegebenen Objekt identisch ist.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-113">Specifies whether this credential is equal to the specified object.</span></span></summary>
        <returns><span data-ttu-id="6a0c1-114">"true", wenn diese Anmeldeinformationen mit dem bestimmten Objekt gleich sind; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="6a0c1-114">true if this credential is equal with the specific object; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmCredential.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="admCredential.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="6a0c1-115">Ruft den Hashcode für die Anmeldeinformationen ab.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-115">Retrieves the hash code for the credential.</span></span></summary>
        <returns><span data-ttu-id="6a0c1-116">Der Hashcode für die Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-116">The hash code for the credential.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidate">
      <MemberSignature Language="C#" Value="protected override void OnValidate (bool allowLocalMockPns);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidate(bool allowLocalMockPns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.AdmCredential.OnValidate(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidate (allowLocalMockPns As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnValidate : bool -&gt; unit" Usage="admCredential.OnValidate allowLocalMockPns" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="allowLocalMockPns" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="allowLocalMockPns"><span data-ttu-id="6a0c1-117">"true", um lokale simulierten PNS zu ermöglichen; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="6a0c1-117">true to allow local mock PNS; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="6a0c1-118">Überprüft die Amazon Device Messaging-Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-118">Validates the Amazon Device Messaging credentials.</span></span></summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Runtime.Serialization.InvalidDataContractException" />
      </Docs>
    </Member>
    <Member MemberName="SendUrlTemplate">
      <MemberSignature Language="C#" Value="public string SendUrlTemplate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SendUrlTemplate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.AdmCredential.SendUrlTemplate" />
      <MemberSignature Language="VB.NET" Value="Public Property SendUrlTemplate As String" />
      <MemberSignature Language="F#" Value="member this.SendUrlTemplate : string with get, set" Usage="Microsoft.Azure.NotificationHubs.AdmCredential.SendUrlTemplate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6a0c1-119">Abrufen oder Festlegen der sendende URL-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-119">Gets or sets the sending URL template.</span></span></summary>
        <value><span data-ttu-id="6a0c1-120">Die sendende URL-Vorlage.</span><span class="sxs-lookup"><span data-stu-id="6a0c1-120">The sending URL template.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
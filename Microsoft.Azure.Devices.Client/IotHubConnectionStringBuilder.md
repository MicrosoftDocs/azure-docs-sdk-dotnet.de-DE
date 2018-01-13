<Type Name="IotHubConnectionStringBuilder" FullName="Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder">
  <TypeSignature Language="C#" Value="public sealed class IotHubConnectionStringBuilder" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit IotHubConnectionStringBuilder extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class IotHubConnectionStringBuilder" />
  <TypeSignature Language="F#" Value="type IotHubConnectionStringBuilder = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b8061-101">Erstellt eine Verbindungszeichenfolge für den IoT Hub-Dienst auf Grundlage der Eigenschaften, die durch den Benutzer ausgefüllt.</span><span class="sxs-lookup"><span data-stu-id="b8061-101">Builds a connection string for the IoT Hub service based on the properties populated by the user.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AuthenticationMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Devices.Client.IAuthenticationMethod AuthenticationMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Devices.Client.IAuthenticationMethod AuthenticationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.AuthenticationMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationMethod As IAuthenticationMethod" />
      <MemberSignature Language="F#" Value="member this.AuthenticationMethod : Microsoft.Azure.Devices.Client.IAuthenticationMethod with get, set" Usage="Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.AuthenticationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.IAuthenticationMethod</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b8061-102">Ruft ab oder legt die Authentifizierungsmethode mit dem IoT Hub-Dienst verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="b8061-102">Gets or sets the authentication method to be used with the IoT Hub service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder Create (string iotHubConnectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder Create(string iotHubConnectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.Create(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (iotHubConnectionString As String) As IotHubConnectionStringBuilder" />
      <MemberSignature Language="F#" Value="static member Create : string -&gt; Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" Usage="Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.Create iotHubConnectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="iotHubConnectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="iotHubConnectionString"><span data-ttu-id="b8061-103">Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="b8061-103">The connection string.</span></span></param>
        <summary>
            <span data-ttu-id="b8061-104">Erstellt eine Verbindungszeichenfolge, die basierend auf den Hostnamen des IoT Hub und die Authentifizierungsmethode, die als Parameter übergeben.</span><span class="sxs-lookup"><span data-stu-id="b8061-104">Creates a connection string based on the hostname of the IoT Hub and the authentication method passed as a parameter.</span></span>
            </summary>
        <returns><span data-ttu-id="b8061-105">Eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" /> Klasse mit einer Verbindungszeichenfolge aufgefüllt.</span><span class="sxs-lookup"><span data-stu-id="b8061-105">A new instance of the <see cref="T:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" /> class with a populated connection string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder Create (string hostname, Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder Create(string hostname, class Microsoft.Azure.Devices.Client.IAuthenticationMethod authenticationMethod) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.Create(System.String,Microsoft.Azure.Devices.Client.IAuthenticationMethod)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (hostname As String, authenticationMethod As IAuthenticationMethod) As IotHubConnectionStringBuilder" />
      <MemberSignature Language="F#" Value="static member Create : string * Microsoft.Azure.Devices.Client.IAuthenticationMethod -&gt; Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" Usage="Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.Create (hostname, authenticationMethod)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostname" Type="System.String" />
        <Parameter Name="authenticationMethod" Type="Microsoft.Azure.Devices.Client.IAuthenticationMethod" />
      </Parameters>
      <Docs>
        <param name="hostname"><span data-ttu-id="b8061-106">Der vollständig qualifizierte DNS-Hostname des IoT Hub</span><span class="sxs-lookup"><span data-stu-id="b8061-106">The fully-qualified DNS hostname of IoT Hub</span></span></param>
        <param name="authenticationMethod"><span data-ttu-id="b8061-107">Die Authentifizierungsmethode, die verwendet wird</span><span class="sxs-lookup"><span data-stu-id="b8061-107">The authentication method that is used</span></span></param>
        <summary>
            <span data-ttu-id="b8061-108">Erstellt eine Verbindungszeichenfolge, die basierend auf den Hostnamen des IoT Hub und die Authentifizierungsmethode, die als Parameter übergeben.</span><span class="sxs-lookup"><span data-stu-id="b8061-108">Creates a connection string based on the hostname of the IoT Hub and the authentication method passed as a parameter.</span></span>
            </summary>
        <returns><span data-ttu-id="b8061-109">Eine neue Instanz der dem <see cref="T:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" /> Klasse mit einer Verbindungszeichenfolge aufgefüllt.</span><span class="sxs-lookup"><span data-stu-id="b8061-109">A new instance of the <see cref="T:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" /> class with a populated connection string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceId">
      <MemberSignature Language="C#" Value="public string DeviceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.DeviceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeviceId As String" />
      <MemberSignature Language="F#" Value="member this.DeviceId : string" Usage="Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.DeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b8061-110">Ruft die Geräte-ID des Geräts Herstellen einer Verbindung mit dem Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="b8061-110">Gets the device identifier of the device connecting to the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayHostName">
      <MemberSignature Language="C#" Value="public string GatewayHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.GatewayHostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GatewayHostName As String" />
      <MemberSignature Language="F#" Value="member this.GatewayHostName : string" Usage="Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.GatewayHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b8061-111">Ruft ab, der optionale Name des Gateways für die Verbindung</span><span class="sxs-lookup"><span data-stu-id="b8061-111">Gets the optional name of the gateway to connect to</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string with get, set" Usage="Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b8061-112">Ruft ab oder legt den Wert für den vollqualifizierten DNS-Hostnamen des Diensts IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="b8061-112">Gets or sets the value of the fully-qualified DNS hostname of the IoT Hub service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKey">
      <MemberSignature Language="C#" Value="public string SharedAccessKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.SharedAccessKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SharedAccessKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKey : string" Usage="Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.SharedAccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b8061-113">Ruft den SAS-Schlüssel für die Verbindung mit dem IoT Hub-Dienst verwendet.</span><span class="sxs-lookup"><span data-stu-id="b8061-113">Gets the shared access key used to connect to the IoT Hub service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessKeyName">
      <MemberSignature Language="C#" Value="public string SharedAccessKeyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.SharedAccessKeyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SharedAccessKeyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessKeyName : string" Usage="Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.SharedAccessKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b8061-114">Ruft den Namen der freigegebenen auf Schlüssel verwendet, um das Gerät mit dem IoT Hub-Dienst herzustellen.</span><span class="sxs-lookup"><span data-stu-id="b8061-114">Gets the shared acess key name used to connect the device to the IoT Hub service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessSignature">
      <MemberSignature Language="C#" Value="public string SharedAccessSignature { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessSignature" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.SharedAccessSignature" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SharedAccessSignature As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessSignature : string" Usage="Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.SharedAccessSignature" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b8061-115">Ruft die SAS, die zur Verbindung mit dem IoT Hub-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="b8061-115">Gets the shared access signature used to connect to the IoT Hub service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override sealed string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides NotOverridable Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="iotHubConnectionStringBuilder.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b8061-116">Erzeugt die Verbindungszeichenfolge auf den Werten basierend der <see cref="T:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" /> Instanzeigenschaften.</span><span class="sxs-lookup"><span data-stu-id="b8061-116">Produces the connection string based on the values of the <see cref="T:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder" /> instance properties.</span></span>
            </summary>
        <returns><span data-ttu-id="b8061-117">Eine ordnungsgemäß formatierte Verbindungszeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="b8061-117">A properly formatted connection string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsingX509Cert">
      <MemberSignature Language="C#" Value="public bool UsingX509Cert { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UsingX509Cert" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.UsingX509Cert" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsingX509Cert As Boolean" />
      <MemberSignature Language="F#" Value="member this.UsingX509Cert : bool" Usage="Microsoft.Azure.Devices.Client.IotHubConnectionStringBuilder.UsingX509Cert" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
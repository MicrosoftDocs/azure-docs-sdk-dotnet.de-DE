<Type Name="BaiduCredential" FullName="Microsoft.Azure.NotificationHubs.BaiduCredential">
  <TypeSignature Language="C#" Value="public class BaiduCredential : Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BaiduCredential extends Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.BaiduCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class BaiduCredential&#xA;Inherits PnsCredential" />
  <TypeSignature Language="F#" Value="type BaiduCredential = class&#xA;    inherit PnsCredential" />
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
      <AttributeName>System.Runtime.Serialization.DataContract(Name="BaiduCredential", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f3670-101">Stellt Baidu-Anmeldeinformationen</span><span class="sxs-lookup"><span data-stu-id="f3670-101">Represents Baidu credentials</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaiduCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f3670-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.BaiduCredential" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f3670-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.BaiduCredential" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaiduCredential (string baiduApiKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string baiduApiKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduCredential.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baiduApiKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.BaiduCredential : string -&gt; Microsoft.Azure.NotificationHubs.BaiduCredential" Usage="new Microsoft.Azure.NotificationHubs.BaiduCredential baiduApiKey" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baiduApiKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="baiduApiKey"><span data-ttu-id="f3670-103">Der Baidu-API-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="f3670-103">The Baidu API key.</span></span></param>
        <summary>
            <span data-ttu-id="f3670-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.BaiduCredential" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f3670-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.NotificationHubs.BaiduCredential" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaiduApiKey">
      <MemberSignature Language="C#" Value="public string BaiduApiKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaiduApiKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.BaiduCredential.BaiduApiKey" />
      <MemberSignature Language="VB.NET" Value="Public Property BaiduApiKey As String" />
      <MemberSignature Language="F#" Value="member this.BaiduApiKey : string with get, set" Usage="Microsoft.Azure.NotificationHubs.BaiduCredential.BaiduApiKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3670-105">Ruft ab oder legt den Baidu-API-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="f3670-105">Gets or sets the Baidu API key.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f3670-106">Der Baidu-API-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="f3670-106">The Baidu API key.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaiduEndPoint">
      <MemberSignature Language="C#" Value="public string BaiduEndPoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaiduEndPoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.BaiduCredential.BaiduEndPoint" />
      <MemberSignature Language="VB.NET" Value="Public Property BaiduEndPoint As String" />
      <MemberSignature Language="F#" Value="member this.BaiduEndPoint : string with get, set" Usage="Microsoft.Azure.NotificationHubs.BaiduCredential.BaiduEndPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3670-107">Abrufen oder Festlegen der Baidu-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="f3670-107">Gets or sets the Baidu end point.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f3670-108">Der Baidu-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="f3670-108">The Baidu end point.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaiduSecretKey">
      <MemberSignature Language="C#" Value="public string BaiduSecretKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaiduSecretKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.BaiduCredential.BaiduSecretKey" />
      <MemberSignature Language="VB.NET" Value="Public Property BaiduSecretKey As String" />
      <MemberSignature Language="F#" Value="member this.BaiduSecretKey : string with get, set" Usage="Microsoft.Azure.NotificationHubs.BaiduCredential.BaiduSecretKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f3670-109">Ruft ab oder legt den Baidu für den geheimen Schlüssel fest.</span><span class="sxs-lookup"><span data-stu-id="f3670-109">Gets or sets the Baidu secret key.</span></span>
            </summary>
        <value>
            <span data-ttu-id="f3670-110">Der geheime Schlüssel des Baidu.</span><span class="sxs-lookup"><span data-stu-id="f3670-110">The Baidu secret key.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduCredential.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="baiduCredential.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj"><span data-ttu-id="f3670-111">Der <see cref="T:System.Object" />, der mit dieser Instanz verglichen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3670-111">The <see cref="T:System.Object" /> to compare with this instance.</span></span></param>
        <summary>
            <span data-ttu-id="f3670-112">Bestimmt, ob das angegebene <see cref="T:System.Object" />, gleich dieser Instanz ist.</span><span class="sxs-lookup"><span data-stu-id="f3670-112">Determines whether the specified <see cref="T:System.Object" />, is equal to this instance.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="f3670-113"><c>"true"</c> Wenn das angegebene <see cref="T:System.Object" /> gleich dieser Instanz ist, andernfalls <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="f3670-113"><c>true</c> if the specified <see cref="T:System.Object" /> is equal to this instance; otherwise, <c>false</c>.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduCredential.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="baiduCredential.GetHashCode " />
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
        <summary>
            <span data-ttu-id="f3670-114">Gibt einen Hashcode für diese Instanz zurück.</span><span class="sxs-lookup"><span data-stu-id="f3670-114">Returns a hash code for this instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f3670-115">Ein Hashcode für diese Instanz, der zur Verwendung in Hashalgorithmen und Hashdatenstrukturen, z. B. einer Hashtabelle, geeignet ist.</span><span class="sxs-lookup"><span data-stu-id="f3670-115">A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.</span></span> 
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidate">
      <MemberSignature Language="C#" Value="protected override void OnValidate (bool allowLocalMockPns);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidate(bool allowLocalMockPns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduCredential.OnValidate(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidate (allowLocalMockPns As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnValidate : bool -&gt; unit" Usage="baiduCredential.OnValidate allowLocalMockPns" />
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
        <param name="allowLocalMockPns"><span data-ttu-id="f3670-116">"true", um lokale simulierten PNS zu ermöglichen; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="f3670-116">true to allow local mock PNS; otherwise, false.</span></span></param>
        <summary>
            <span data-ttu-id="f3670-117">Überprüft die Anmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="f3670-117">Validates the credential.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Runtime.Serialization.InvalidDataContractException" />
      </Docs>
    </Member>
  </Members>
</Type>
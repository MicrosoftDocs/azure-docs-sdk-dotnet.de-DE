<Type Name="MobileServiceClient" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceClient">
  <TypeSignature Language="C#" Value="public class MobileServiceClient : IDisposable, Microsoft.WindowsAzure.MobileServices.IMobileServiceClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceClient extends System.Object implements class Microsoft.WindowsAzure.MobileServices.IMobileServiceClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceClient" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceClient&#xA;Implements IDisposable, IMobileServiceClient" />
  <TypeSignature Language="F#" Value="type MobileServiceClient = class&#xA;    interface IMobileServiceClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.MobileServices.IMobileServiceClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1e236-101">Bietet einfachen Zugriff auf Microsoft Azure Mobile Service.</span><span class="sxs-lookup"><span data-stu-id="1e236-101">Provides basic access to a Microsoft Azure Mobile Service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MobileServiceClient ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
             <span data-ttu-id="1e236-102">Dies ist ausschließlich für Komponententests</span><span class="sxs-lookup"><span data-stu-id="1e236-102">This is for unit testing only</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceClient (string mobileAppUri, params System.Net.Http.HttpMessageHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string mobileAppUri, class System.Net.Http.HttpMessageHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.#ctor(System.String,System.Net.Http.HttpMessageHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (mobileAppUri As String, ParamArray handlers As HttpMessageHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceClient : string * System.Net.Http.HttpMessageHandler[] -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceClient" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceClient (mobileAppUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mobileAppUri" Type="System.String" />
        <Parameter Name="handlers" Type="System.Net.Http.HttpMessageHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="mobileAppUri">
            <span data-ttu-id="1e236-103">Absoluter URI der mobilen Microsoft Azure-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="1e236-103">Absolute URI of the Microsoft Azure Mobile App.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="1e236-104">Kette von <see cref="T:System.Net.Http.HttpMessageHandler" /> Instanzen.</span><span class="sxs-lookup"><span data-stu-id="1e236-104">Chain of <see cref="T:System.Net.Http.HttpMessageHandler" /> instances.</span></span>
            <span data-ttu-id="1e236-105">Alle außer der letzten muss <see cref="T:System.Net.Http.DelegatingHandler" />s.</span><span class="sxs-lookup"><span data-stu-id="1e236-105">All but the last should be <see cref="T:System.Net.Http.DelegatingHandler" />s.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e236-106">Initialisiert eine neue Instanz der MobileServiceClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1e236-106">Initializes a new instance of the MobileServiceClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceClient (Uri mobileAppUri, params System.Net.Http.HttpMessageHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri mobileAppUri, class System.Net.Http.HttpMessageHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.#ctor(System.Uri,System.Net.Http.HttpMessageHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (mobileAppUri As Uri, ParamArray handlers As HttpMessageHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.MobileServices.MobileServiceClient : Uri * System.Net.Http.HttpMessageHandler[] -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceClient" Usage="new Microsoft.WindowsAzure.MobileServices.MobileServiceClient (mobileAppUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mobileAppUri" Type="System.Uri" />
        <Parameter Name="handlers" Type="System.Net.Http.HttpMessageHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="mobileAppUri">
            <span data-ttu-id="1e236-107">Absoluter URI der mobilen Microsoft Azure-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="1e236-107">Absolute URI of the Microsoft Azure Mobile App.</span></span>
            </param>
        <param name="handlers">
            <span data-ttu-id="1e236-108">Kette von <see cref="T:System.Net.Http.HttpMessageHandler" /> Instanzen.</span><span class="sxs-lookup"><span data-stu-id="1e236-108">Chain of <see cref="T:System.Net.Http.HttpMessageHandler" /> instances.</span></span>
            <span data-ttu-id="1e236-109">Alle außer der letzten muss <see cref="T:System.Net.Http.DelegatingHandler" />s.</span><span class="sxs-lookup"><span data-stu-id="1e236-109">All but the last should be <see cref="T:System.Net.Http.DelegatingHandler" />s.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e236-110">Initialisiert eine neue Instanz der MobileServiceClient-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1e236-110">Initializes a new instance of the MobileServiceClient class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AlternateLoginHost">
      <MemberSignature Language="C#" Value="public Uri AlternateLoginHost { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri AlternateLoginHost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.AlternateLoginHost" />
      <MemberSignature Language="VB.NET" Value="Public Property AlternateLoginHost As Uri" />
      <MemberSignature Language="F#" Value="member this.AlternateLoginHost : Uri with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.AlternateLoginHost" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.AlternateLoginHost</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e236-111">Alternative URI für login</span><span class="sxs-lookup"><span data-stu-id="1e236-111">Alternate URI for login</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentUser">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.MobileServiceUser CurrentUser { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.MobileServiceUser CurrentUser" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.CurrentUser" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentUser As MobileServiceUser" />
      <MemberSignature Language="F#" Value="member this.CurrentUser : Microsoft.WindowsAzure.MobileServices.MobileServiceUser with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.CurrentUser" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.CurrentUser</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.MobileServiceUser</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e236-112">Der aktuelle authentifizierte Benutzer, die nach einem erfolgreichen Aufruf von MobileServiceClient.Login() bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="1e236-112">The current authenticated user provided after a successful call to MobileServiceClient.Login().</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultDatabasePath">
      <MemberSignature Language="C#" Value="public static string DefaultDatabasePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property string DefaultDatabasePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.DefaultDatabasePath" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property DefaultDatabasePath As String" />
      <MemberSignature Language="F#" Value="member this.DefaultDatabasePath : string" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.DefaultDatabasePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e236-113">Der Speicherort der Dateien müssen wir für offline-Synchronisierung erstellen</span><span class="sxs-lookup"><span data-stu-id="1e236-113">The location of any files we need to create for offline-sync</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="mobileServiceClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e236-114">Implementierung des<see cref="T:System.IDisposable" /></span><span class="sxs-lookup"><span data-stu-id="1e236-114">Implemenation of <see cref="T:System.IDisposable" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="mobileServiceClient.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">
            <span data-ttu-id="1e236-115">Gibt an, wenn von der Dispose()-Methode oder den Finalizer aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="1e236-115">Indicates if being called from the Dispose() method or the finalizer.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e236-116">Implementierung des <see cref="T:System.IDisposable" /> für abgeleitete Klassen zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="1e236-116">Implemenation of <see cref="T:System.IDisposable" /> for derived classes to use.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnsureFileExists">
      <MemberSignature Language="C#" Value="public static void EnsureFileExists (string path);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void EnsureFileExists(string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.EnsureFileExists(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Sub EnsureFileExists (path As String)" />
      <MemberSignature Language="F#" Value="static member EnsureFileExists : string -&gt; unit" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.EnsureFileExists path" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="1e236-117">Der Pfadname eine vollqualifizierte überprüfen</span><span class="sxs-lookup"><span data-stu-id="1e236-117">The fully-qualified pathname to check</span></span></param>
        <summary>
            <span data-ttu-id="1e236-118">Stellt sicher, dass eine Datei vorhanden ist, erstellen sie bei Bedarf</span><span class="sxs-lookup"><span data-stu-id="1e236-118">Ensures that a file exists, creating it if necessary</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventManager">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager EventManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager EventManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.EventManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EventManager As IMobileServiceEventManager" />
      <MemberSignature Language="F#" Value="member this.EventManager : Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.EventManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Eventing.IMobileServiceEventManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e236-119">Die Ereignis-Manager, der verfügbar gemacht werden und den ereignisdatenstrom von den mobile Services-Typen zu veröffentlichen und Verarbeiten von Ereignissen verwendeten verwaltet.</span><span class="sxs-lookup"><span data-stu-id="1e236-119">The event manager that exposes and manages the event stream used by the mobile services types to publish and consume events.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSyncTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable GetSyncTable (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable GetSyncTable(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.GetSyncTable(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSyncTable (tableName As String) As IMobileServiceSyncTable" />
      <MemberSignature Language="F#" Value="abstract member GetSyncTable : string -&gt; Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&#xA;override this.GetSyncTable : string -&gt; Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" Usage="mobileServiceClient.GetSyncTable tableName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.GetSyncTable(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName"><span data-ttu-id="1e236-120">Der Name der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="1e236-120">The name of the table.</span></span></param>
        <summary>
            <span data-ttu-id="1e236-121">Gibt eine <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" /> Instanz, die nicht typisierte Datenvorgänge für diese Tabelle bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="1e236-121">Returns a <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable" /> instance, which provides untyped data operations for that table.</span></span>
            </summary>
        <returns><span data-ttu-id="1e236-122">den Tisch.</span><span class="sxs-lookup"><span data-stu-id="1e236-122">The table.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSyncTable&lt;T&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt; GetSyncTable&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1&lt;!!T&gt; GetSyncTable&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.GetSyncTable``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSyncTable(Of T) () As IMobileServiceSyncTable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetSyncTable : unit -&gt; Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt;&#xA;override this.GetSyncTable : unit -&gt; Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;'T&gt;" Usage="mobileServiceClient.GetSyncTable " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.GetSyncTable``1</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="1e236-123">Der Typ der Instanzen in der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="1e236-123">The type of the instances in the table.</span></span>
            </typeparam>
        <summary>
            <span data-ttu-id="1e236-124">Gibt eine <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1" /> -Instanz, die stark typisierte Datenvorgänge für lokale Tabelle bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="1e236-124">Returns a <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncTable`1" /> instance, which provides strongly typed data operations for local table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e236-125">den Tisch.</span><span class="sxs-lookup"><span data-stu-id="1e236-125">The table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTable">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTable GetTable (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable GetTable(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.GetTable(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTable (tableName As String) As IMobileServiceTable" />
      <MemberSignature Language="F#" Value="abstract member GetTable : string -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&#xA;override this.GetTable : string -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" Usage="mobileServiceClient.GetTable tableName" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.GetTable(System.String)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName">
            <span data-ttu-id="1e236-126">Der Name der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="1e236-126">The name of the table.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e236-127">Gibt eine <see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" /> Instanz, die nicht typisierte Datenvorgänge für diese Tabelle bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="1e236-127">Returns a <see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable" /> instance, which provides untyped data operations for that table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e236-128">den Tisch.</span><span class="sxs-lookup"><span data-stu-id="1e236-128">The table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTable&lt;T&gt;">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;T&gt; GetTable&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1&lt;!!T&gt; GetTable&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.GetTable``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetTable(Of T) () As IMobileServiceTable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetTable : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;'T&gt;&#xA;override this.GetTable : unit -&gt; Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;'T&gt;" Usage="mobileServiceClient.GetTable " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.GetTable``1</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.IMobileServiceTable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="1e236-129">Der Typ der Instanzen in der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="1e236-129">The type of the instances in the table.</span></span>
            </typeparam>
        <summary>
            <span data-ttu-id="1e236-130">Gibt eine <see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1" /> Instanz, die stark typisierte Datenvorgänge für diese Tabelle bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="1e236-130">Returns a <see cref="T:Microsoft.WindowsAzure.MobileServices.IMobileServiceTable`1" /> instance, which provides strongly typed data operations for that table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e236-131">den Tisch.</span><span class="sxs-lookup"><span data-stu-id="1e236-131">The table.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstallationId">
      <MemberSignature Language="C#" Value="public string InstallationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstallationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InstallationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstallationId As String" />
      <MemberSignature Language="F#" Value="member this.InstallationId : string" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InstallationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e236-132">Die Id zur Identifizierung dieser Installation der Anwendung um Telemetriedaten bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="1e236-132">The id used to identify this installation of the application to provide telemetry data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync (string apiName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync(string apiName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;&#xA;override this.InvokeApiAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName"><span data-ttu-id="1e236-133">Der Name der benutzerdefinierten API.</span><span class="sxs-lookup"><span data-stu-id="1e236-133">The name of the custom API.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1e236-134">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="1e236-134">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="1e236-135">Ruft eine benutzerdefinierte API eines Microsoft Azure Mobile Service mit HTTP POST.</span><span class="sxs-lookup"><span data-stu-id="1e236-135">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using an HTTP POST.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync (string apiName, Newtonsoft.Json.Linq.JToken body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync(string apiName, class Newtonsoft.Json.Linq.JToken body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync(System.String,Newtonsoft.Json.Linq.JToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * Newtonsoft.Json.Linq.JToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;&#xA;override this.InvokeApiAsync : string * Newtonsoft.Json.Linq.JToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,Newtonsoft.Json.Linq.JToken,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="body" Type="Newtonsoft.Json.Linq.JToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName"><span data-ttu-id="1e236-136">Der Name der benutzerdefinierten API.</span><span class="sxs-lookup"><span data-stu-id="1e236-136">The name of the custom API.</span></span></param>
        <param name="body"><span data-ttu-id="1e236-137">Der Wert, der als HTTP-Text gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="1e236-137">The value to be sent as the HTTP body.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1e236-138">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="1e236-138">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="1e236-139">Ruft eine benutzerdefinierte API eines Microsoft Azure Mobile Service mit HTTP POST, mit Unterstützung für das Senden von HTTP-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="1e236-139">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using an HTTP POST, with support for sending HTTP content.</span></span>
            </summary>
        <returns><span data-ttu-id="1e236-140">Der Antwortinhalt des Aufrufs der benutzerdefinierten api.</span><span class="sxs-lookup"><span data-stu-id="1e236-140">The response content from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync (string apiName, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync(string apiName, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync(System.String,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;&#xA;override this.InvokeApiAsync : string * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, method, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName"><span data-ttu-id="1e236-141">Der Name der benutzerdefinierten API.</span><span class="sxs-lookup"><span data-stu-id="1e236-141">The name of the custom API.</span></span></param>
        <param name="method"><span data-ttu-id="1e236-142">Die HTTP-Methode.</span><span class="sxs-lookup"><span data-stu-id="1e236-142">The HTTP method.</span></span></param>
        <param name="parameters">
            <span data-ttu-id="1e236-143">Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.</span><span class="sxs-lookup"><span data-stu-id="1e236-143">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="1e236-144">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="1e236-144">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="1e236-145">Ruft eine benutzerdefinierte API eines Microsoft Azure Mobile Service mithilfe der angegebenen HTTP-Methode.</span><span class="sxs-lookup"><span data-stu-id="1e236-145">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using the specified HTTP Method.</span></span>
            <span data-ttu-id="1e236-146">Zusätzliche Daten wird über die Abfragezeichenfolge gesendet.</span><span class="sxs-lookup"><span data-stu-id="1e236-146">Additional data will sent to through the query string.</span></span>
            </summary>
        <returns><span data-ttu-id="1e236-147">Der Antwortinhalt des Aufrufs der benutzerdefinierten api.</span><span class="sxs-lookup"><span data-stu-id="1e236-147">The response content from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync (string apiName, Newtonsoft.Json.Linq.JToken body, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Newtonsoft.Json.Linq.JToken&gt; InvokeApiAsync(string apiName, class Newtonsoft.Json.Linq.JToken body, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync(System.String,Newtonsoft.Json.Linq.JToken,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * Newtonsoft.Json.Linq.JToken * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;&#xA;override this.InvokeApiAsync : string * Newtonsoft.Json.Linq.JToken * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, body, method, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,Newtonsoft.Json.Linq.JToken,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceClient/&lt;InvokeApiAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Newtonsoft.Json.Linq.JToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="body" Type="Newtonsoft.Json.Linq.JToken" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName"><span data-ttu-id="1e236-148">Der Name der benutzerdefinierten API.</span><span class="sxs-lookup"><span data-stu-id="1e236-148">The name of the custom API.</span></span></param>
        <param name="body"><span data-ttu-id="1e236-149">Der Wert, der als HTTP-Text gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="1e236-149">The value to be sent as the HTTP body.</span></span></param>
        <param name="method"><span data-ttu-id="1e236-150">Die HTTP-Methode.</span><span class="sxs-lookup"><span data-stu-id="1e236-150">The HTTP Method.</span></span></param>
        <param name="parameters">
            <span data-ttu-id="1e236-151">Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.</span><span class="sxs-lookup"><span data-stu-id="1e236-151">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="1e236-152">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="1e236-152">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="1e236-153">Ruft eine benutzerdefinierte API eines Microsoft Azure Mobile Service mithilfe der angegebenen HTTP-Methode.</span><span class="sxs-lookup"><span data-stu-id="1e236-153">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using the specified HTTP method.</span></span>
            <span data-ttu-id="1e236-154">Zusätzliche Daten können jedoch den HTTP-Inhalt oder die Abfragezeichenfolge gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="1e236-154">Additional data can be sent though the HTTP content or the query string.</span></span>
            </summary>
        <returns><span data-ttu-id="1e236-155">Der Antwortinhalt des Aufrufs der benutzerdefinierten api.</span><span class="sxs-lookup"><span data-stu-id="1e236-155">The response content from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt; InvokeApiAsync (string apiName, System.Net.Http.HttpContent content, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; requestHeaders, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Net.Http.HttpResponseMessage&gt; InvokeApiAsync(string apiName, class System.Net.Http.HttpContent content, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; requestHeaders, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync(System.String,System.Net.Http.HttpContent,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function InvokeApiAsync (apiName As String, content As HttpContent, method As HttpMethod, requestHeaders As IDictionary(Of String, String), parameters As IDictionary(Of String, String)) As Task(Of HttpResponseMessage)" />
      <MemberSignature Language="F#" Value="member this.InvokeApiAsync : string * System.Net.Http.HttpContent * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, content, method, requestHeaders, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceClient/&lt;InvokeApiAsync&gt;d__74))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="content" Type="System.Net.Http.HttpContent" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="requestHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="apiName"><span data-ttu-id="1e236-156">Der Name der benutzerdefinierten API.</span><span class="sxs-lookup"><span data-stu-id="1e236-156">The name of the custom AP.</span></span></param>
        <param name="content"><span data-ttu-id="1e236-157">Der HTTP-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="1e236-157">The HTTP content.</span></span></param>
        <param name="method"><span data-ttu-id="1e236-158">Die HTTP-Methode.</span><span class="sxs-lookup"><span data-stu-id="1e236-158">The HTTP method.</span></span></param>
        <param name="requestHeaders">
            <span data-ttu-id="1e236-159">Ein Wörterbuch mit benutzerdefinierten Headern HttpRequest einschließt.</span><span class="sxs-lookup"><span data-stu-id="1e236-159">A dictionary of user-defined headers to include in the HttpRequest.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1e236-160">Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.</span><span class="sxs-lookup"><span data-stu-id="1e236-160">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e236-161">Ruft eine benutzerdefinierte API eines Windows Azure Mobile Service mithilfe der angegebenen HTTP-Methode.</span><span class="sxs-lookup"><span data-stu-id="1e236-161">Invokes a user-defined custom API of a Windows Azure Mobile Service using the specified HttpMethod.</span></span>
            <span data-ttu-id="1e236-162">Zusätzliche Daten können jedoch den HTTP-Inhalt oder die Abfragezeichenfolge gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="1e236-162">Additional data can be sent though the HTTP content or the query string.</span></span>
            </summary>
        <returns><span data-ttu-id="1e236-163">Der HTTP-Antwort des Aufrufs der benutzerdefinierten api.</span><span class="sxs-lookup"><span data-stu-id="1e236-163">The HTTP Response from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt; InvokeApiAsync (string apiName, System.Net.Http.HttpContent content, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; requestHeaders, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Net.Http.HttpResponseMessage&gt; InvokeApiAsync(string apiName, class System.Net.Http.HttpContent content, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; requestHeaders, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync(System.String,System.Net.Http.HttpContent,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Net.Http.HttpContent * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;&#xA;override this.InvokeApiAsync : string * System.Net.Http.HttpContent * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, content, method, requestHeaders, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync(System.String,System.Net.Http.HttpContent,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceClient/&lt;InvokeApiAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Net.Http.HttpResponseMessage&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="content" Type="System.Net.Http.HttpContent" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="requestHeaders" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiName"><span data-ttu-id="1e236-164">Der Name der benutzerdefinierten API.</span><span class="sxs-lookup"><span data-stu-id="1e236-164">The name of the custom AP.</span></span></param>
        <param name="content"><span data-ttu-id="1e236-165">Der HTTP-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="1e236-165">The HTTP content.</span></span></param>
        <param name="method"><span data-ttu-id="1e236-166">Die HTTP-Methode.</span><span class="sxs-lookup"><span data-stu-id="1e236-166">The HTTP method.</span></span></param>
        <param name="requestHeaders">
            <span data-ttu-id="1e236-167">Ein Wörterbuch mit benutzerdefinierten Headern HttpRequest einschließt.</span><span class="sxs-lookup"><span data-stu-id="1e236-167">A dictionary of user-defined headers to include in the HttpRequest.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1e236-168">Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.</span><span class="sxs-lookup"><span data-stu-id="1e236-168">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="1e236-169">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="1e236-169">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="1e236-170">Ruft eine benutzerdefinierte API eines Windows Azure Mobile Service mithilfe der angegebenen HTTP-Methode.</span><span class="sxs-lookup"><span data-stu-id="1e236-170">Invokes a user-defined custom API of a Windows Azure Mobile Service using the specified HttpMethod.</span></span>
            <span data-ttu-id="1e236-171">Zusätzliche Daten können jedoch den HTTP-Inhalt oder die Abfragezeichenfolge gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="1e236-171">Additional data can be sent though the HTTP content or the query string.</span></span>
            </summary>
        <returns><span data-ttu-id="1e236-172">Der HTTP-Antwort des Aufrufs der benutzerdefinierten api.</span><span class="sxs-lookup"><span data-stu-id="1e236-172">The HTTP Response from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; InvokeApiAsync&lt;T&gt; (string apiName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; InvokeApiAsync&lt;T&gt;(string apiName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync``1(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;&#xA;override this.InvokeApiAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync``1(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="1e236-173">Der Typ der Instanz von Microsoft Azure Mobile Service zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1e236-173">The type of instance returned from the Microsoft Azure Mobile Service.</span></span></typeparam>
        <param name="apiName"><span data-ttu-id="1e236-174">Der Name der benutzerdefinierten API.</span><span class="sxs-lookup"><span data-stu-id="1e236-174">The name of the custom API.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1e236-175">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="1e236-175">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="1e236-176">Ruft eine benutzerdefinierte API eines Microsoft Azure Mobile Service mit HTTP POST.</span><span class="sxs-lookup"><span data-stu-id="1e236-176">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using an HTTP POST.</span></span>
            </summary>
        <returns><span data-ttu-id="1e236-177">Der Antwortinhalt des Aufrufs der benutzerdefinierten api.</span><span class="sxs-lookup"><span data-stu-id="1e236-177">The response content from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; InvokeApiAsync&lt;T&gt; (string apiName, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!T&gt; InvokeApiAsync&lt;T&gt;(string apiName, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync``1(System.String,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;&#xA;override this.InvokeApiAsync : string * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, method, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync``1(System.String,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="1e236-178">Der Typ der Instanz, die an den Microsoft Azure Mobile Service gesendet.</span><span class="sxs-lookup"><span data-stu-id="1e236-178">The type of instance sent to the Microsoft Azure Mobile Service.</span></span></typeparam>
        <param name="apiName"><span data-ttu-id="1e236-179">Der Name der benutzerdefinierten API.</span><span class="sxs-lookup"><span data-stu-id="1e236-179">The name of the custom API.</span></span></param>
        <param name="method"><span data-ttu-id="1e236-180">Die HTTP-Methode.</span><span class="sxs-lookup"><span data-stu-id="1e236-180">The HTTP method.</span></span></param>
        <param name="parameters">
            <span data-ttu-id="1e236-181">Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.</span><span class="sxs-lookup"><span data-stu-id="1e236-181">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="1e236-182">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="1e236-182">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="1e236-183">Ruft eine benutzerdefinierte API eines Microsoft Azure Mobile Service mithilfe der angegebenen HTTP-Methode.</span><span class="sxs-lookup"><span data-stu-id="1e236-183">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using the specified HTTP Method.</span></span>
            <span data-ttu-id="1e236-184">Zusätzliche Daten können mithilfe der Abfragezeichenfolge übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="1e236-184">Additional data can be passed using the query string.</span></span>
            </summary>
        <returns><span data-ttu-id="1e236-185">Der Antwortinhalt des Aufrufs der benutzerdefinierten api.</span><span class="sxs-lookup"><span data-stu-id="1e236-185">The response content from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;U&gt; InvokeApiAsync&lt;T,U&gt; (string apiName, T body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!U&gt; InvokeApiAsync&lt;T, U&gt;(string apiName, !!T body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync``2(System.String,``0,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'U&gt;&#xA;override this.InvokeApiAsync : string * 'T * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'U&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync``2(System.String,``0,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;U&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="body" Type="T" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="1e236-186">Der Typ der Instanz, die an den Microsoft Azure Mobile Service gesendet.</span><span class="sxs-lookup"><span data-stu-id="1e236-186">The type of instance sent to the Microsoft Azure Mobile Service.</span></span></typeparam>
        <typeparam name="U"><span data-ttu-id="1e236-187">Der Typ der Instanz von Microsoft Azure Mobile Service zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1e236-187">The type of instance returned from the Microsoft Azure Mobile Service.</span></span></typeparam>
        <param name="apiName"><span data-ttu-id="1e236-188">Der Name der benutzerdefinierten API.</span><span class="sxs-lookup"><span data-stu-id="1e236-188">The name of the custom API.</span></span></param>
        <param name="body"><span data-ttu-id="1e236-189">Der Wert, der als HTTP-Text gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="1e236-189">The value to be sent as the HTTP body.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="1e236-190">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="1e236-190">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="1e236-191">Ruft eine benutzerdefinierte API eines Microsoft Azure Mobile Service mit HTTP POST mit Unterstützung für das Senden von HTTP-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="1e236-191">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using an HTTP POST with support for sending HTTP content.</span></span>
            </summary>
        <returns><span data-ttu-id="1e236-192">Der Antwortinhalt des Aufrufs der benutzerdefinierten api.</span><span class="sxs-lookup"><span data-stu-id="1e236-192">The response content from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeApiAsync&lt;T,U&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;U&gt; InvokeApiAsync&lt;T,U&gt; (string apiName, T body, System.Net.Http.HttpMethod method, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!!U&gt; InvokeApiAsync&lt;T, U&gt;(string apiName, !!T body, class System.Net.Http.HttpMethod method, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.InvokeApiAsync``2(System.String,``0,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member InvokeApiAsync : string * 'T * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'U&gt;&#xA;override this.InvokeApiAsync : string * 'T * System.Net.Http.HttpMethod * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'U&gt;" Usage="mobileServiceClient.InvokeApiAsync (apiName, body, method, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.InvokeApiAsync``2(System.String,``0,System.Net.Http.HttpMethod,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceClient/&lt;InvokeApiAsync&gt;d__66`2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;U&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
        <TypeParameter Name="U" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="apiName" Type="System.String" />
        <Parameter Name="body" Type="T" />
        <Parameter Name="method" Type="System.Net.Http.HttpMethod" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T"><span data-ttu-id="1e236-193">Der Typ der Instanz, die an den Microsoft Azure Mobile Service gesendet.</span><span class="sxs-lookup"><span data-stu-id="1e236-193">The type of instance sent to the Microsoft Azure Mobile Service.</span></span></typeparam>
        <typeparam name="U"><span data-ttu-id="1e236-194">Der Typ der Instanz von Microsoft Azure Mobile Service zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1e236-194">The type of instance returned from the Microsoft Azure Mobile Service.</span></span></typeparam>
        <param name="apiName"><span data-ttu-id="1e236-195">Der Name der benutzerdefinierten API.</span><span class="sxs-lookup"><span data-stu-id="1e236-195">The name of the custom API.</span></span></param>
        <param name="body"><span data-ttu-id="1e236-196">Der Wert, der als HTTP-Text gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="1e236-196">The value to be sent as the HTTP body.</span></span></param>
        <param name="method"><span data-ttu-id="1e236-197">Die HTTP-Methode.</span><span class="sxs-lookup"><span data-stu-id="1e236-197">The HTTP method.</span></span></param>
        <param name="parameters">
            <span data-ttu-id="1e236-198">Ein Wörterbuch mit benutzerdefinierten Parametern und Werten, die im Anforderungs-URI-Abfragezeichenfolge enthalten.</span><span class="sxs-lookup"><span data-stu-id="1e236-198">A dictionary of user-defined parameters and values to include in the request URI query string.</span></span>
            </param>
        <param name="cancellationToken"><span data-ttu-id="1e236-199">Die <see cref="T:System.Threading.CancellationToken" /> Token beobachten</span><span class="sxs-lookup"><span data-stu-id="1e236-199">The <see cref="T:System.Threading.CancellationToken" /> token to observe</span></span></param>
        <summary>
            <span data-ttu-id="1e236-200">Ruft eine benutzerdefinierte API eines Microsoft Azure Mobile Service mithilfe der angegebenen HTTP-Methode.</span><span class="sxs-lookup"><span data-stu-id="1e236-200">Invokes a user-defined custom API of a Microsoft Azure Mobile Service using the specified HTTP Method.</span></span>
            <span data-ttu-id="1e236-201">Zusätzliche Daten können jedoch den HTTP-Inhalt oder die Abfragezeichenfolge gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="1e236-201">Additional data can be sent though the HTTP content or the query string.</span></span>
            </summary>
        <returns><span data-ttu-id="1e236-202">Der Antwortinhalt des Aufrufs der benutzerdefinierten api.</span><span class="sxs-lookup"><span data-stu-id="1e236-202">The response content from the custom api invocation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginAsync (Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider provider, Newtonsoft.Json.Linq.JObject token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginAsync(valuetype Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider provider, class Newtonsoft.Json.Linq.JObject token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.LoginAsync(Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoginAsync (provider As MobileServiceAuthenticationProvider, token As JObject) As Task(Of MobileServiceUser)" />
      <MemberSignature Language="F#" Value="abstract member LoginAsync : Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider * Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;&#xA;override this.LoginAsync : Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider * Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;" Usage="mobileServiceClient.LoginAsync (provider, token)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.LoginAsync(Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider,Newtonsoft.Json.Linq.JObject)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="provider" Type="Microsoft.WindowsAzure.MobileServices.MobileServiceAuthenticationProvider" />
        <Parameter Name="token" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="provider">
            <span data-ttu-id="1e236-203">Der zu verwendende Authentifizierungsanbieter.</span><span class="sxs-lookup"><span data-stu-id="1e236-203">Authentication provider to use.</span></span>
            </param>
        <param name="token">
            <span data-ttu-id="1e236-204">Anbieterspezifisches Objekt mit vorhandenem OAuth-Token für die Anmeldung.</span><span class="sxs-lookup"><span data-stu-id="1e236-204">Provider specific object with existing OAuth token to log in with.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e236-205">Meldet einen Benutzer in Windows Azure Mobile Service mit dem Anbieter und optionalen Tokenobjekt an.</span><span class="sxs-lookup"><span data-stu-id="1e236-205">Logs a user into a Windows Azure Mobile Service with the provider and optional token object.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e236-206">Aufgabe, die abgeschlossen wird, wenn der Benutzer die Authentifizierung beendet hat.</span><span class="sxs-lookup"><span data-stu-id="1e236-206">Task that will complete when the user has finished authentication.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="1e236-207">Das Tokenobjekt muss abhängig von dem Anbieter formatiert werden.</span><span class="sxs-lookup"><span data-stu-id="1e236-207">The token object needs to be formatted depending on the specific provider.</span></span> <span data-ttu-id="1e236-208">Dies sind einige Beispiele der Formate basierend auf den Anbieter: <list type="bullet"> <item> <term>MicrosoftAccount</term> <description> <code>{"authenticationToken":"&lt;the_authentication_token&gt;"}</code> </description> </item> <item> <term> Facebook</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item><item><term>Google</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item></list></span><span class="sxs-lookup"><span data-stu-id="1e236-208">These are some examples of formats based on the providers: <list type="bullet"><item><term>MicrosoftAccount</term><description><code>{"authenticationToken":"&lt;the_authentication_token&gt;"}</code></description></item><item><term>Facebook</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item><item><term>Google</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item></list></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginAsync (string provider, Newtonsoft.Json.Linq.JObject token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; LoginAsync(string provider, class Newtonsoft.Json.Linq.JObject token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.LoginAsync(System.String,Newtonsoft.Json.Linq.JObject)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoginAsync (provider As String, token As JObject) As Task(Of MobileServiceUser)" />
      <MemberSignature Language="F#" Value="abstract member LoginAsync : string * Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;&#xA;override this.LoginAsync : string * Newtonsoft.Json.Linq.JObject -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;" Usage="mobileServiceClient.LoginAsync (provider, token)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.LoginAsync(System.String,Newtonsoft.Json.Linq.JObject)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="token" Type="Newtonsoft.Json.Linq.JObject" />
      </Parameters>
      <Docs>
        <param name="provider">
            <span data-ttu-id="1e236-209">Der zu verwendende Authentifizierungsanbieter.</span><span class="sxs-lookup"><span data-stu-id="1e236-209">Authentication provider to use.</span></span>
            </param>
        <param name="token">
            <span data-ttu-id="1e236-210">Anbieterspezifisches Objekt mit vorhandenem OAuth-Token für die Anmeldung.</span><span class="sxs-lookup"><span data-stu-id="1e236-210">Provider specific object with existing OAuth token to log in with.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e236-211">Meldet einen Benutzer in Microsoft Azure Mobile Service mit dem Anbieter und optionalen Tokenobjekt an.</span><span class="sxs-lookup"><span data-stu-id="1e236-211">Logs a user into a Microsoft Azure Mobile Service with the provider and optional token object.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e236-212">Aufgabe, die abgeschlossen wird, wenn der Benutzer die Authentifizierung beendet hat.</span><span class="sxs-lookup"><span data-stu-id="1e236-212">Task that will complete when the user has finished authentication.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="1e236-213">Das Tokenobjekt muss abhängig von dem Anbieter formatiert werden.</span><span class="sxs-lookup"><span data-stu-id="1e236-213">The token object needs to be formatted depending on the specific provider.</span></span> <span data-ttu-id="1e236-214">Dies sind einige Beispiele der Formate basierend auf den Anbieter: <list type="bullet"> <item> <term>MicrosoftAccount</term> <description> <code>{"authenticationToken":"&lt;the_authentication_token&gt;"}</code> </description> </item> <item> <term> Facebook</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item><item><term>Google</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item></list></span><span class="sxs-lookup"><span data-stu-id="1e236-214">These are some examples of formats based on the providers: <list type="bullet"><item><term>MicrosoftAccount</term><description><code>{"authenticationToken":"&lt;the_authentication_token&gt;"}</code></description></item><item><term>Facebook</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item><item><term>Google</term><description><code>{"access_token":"&lt;the_access_token&gt;"}</code></description></item></list></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginUriPrefix">
      <MemberSignature Language="C#" Value="public string LoginUriPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LoginUriPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.LoginUriPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property LoginUriPrefix As String" />
      <MemberSignature Language="F#" Value="member this.LoginUriPrefix : string with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.LoginUriPrefix" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.LoginUriPrefix</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e236-215">Präfix für die Endpunkte für die Anmeldung.</span><span class="sxs-lookup"><span data-stu-id="1e236-215">Prefix for the login endpoints.</span></span> <span data-ttu-id="1e236-216">Sofern nichts anderes festgelegt Standardwerte auf /.auth/login</span><span class="sxs-lookup"><span data-stu-id="1e236-216">If not set defaults to /.auth/login</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogoutAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task LogoutAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task LogoutAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.LogoutAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function LogoutAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member LogoutAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.LogoutAsync : unit -&gt; System.Threading.Tasks.Task" Usage="mobileServiceClient.LogoutAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.LogoutAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e236-217">Abmelden eines Benutzers.</span><span class="sxs-lookup"><span data-stu-id="1e236-217">Log a user out.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MobileAppUri">
      <MemberSignature Language="C#" Value="public Uri MobileAppUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri MobileAppUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.MobileAppUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MobileAppUri As Uri" />
      <MemberSignature Language="F#" Value="member this.MobileAppUri : Uri" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.MobileAppUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e236-218">Absoluter URI der mobilen Microsoft Azure-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="1e236-218">Absolute URI of the Microsoft Azure Mobile App.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshUserAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; RefreshUserAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt; RefreshUserAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.RefreshUserAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RefreshUserAsync () As Task(Of MobileServiceUser)" />
      <MemberSignature Language="F#" Value="abstract member RefreshUserAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;&#xA;override this.RefreshUserAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;" Usage="mobileServiceClient.RefreshUserAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.RefreshUserAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.WindowsAzure.MobileServices.MobileServiceClient/&lt;RefreshUserAsync&gt;d__62))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.MobileServices.MobileServiceUser&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e236-219">Aktualisiert das Zugriffstoken mit dem Identitätsanbieter für den angemeldeten Benutzer.</span><span class="sxs-lookup"><span data-stu-id="1e236-219">Refreshes access token with the identity provider for the logged in user.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e236-220">Aufgabe, die abgeschlossen wird, wenn der Benutzer die Aktualisierung von Zugriffstoken abgeschlossen hat</span><span class="sxs-lookup"><span data-stu-id="1e236-220">Task that will complete when the user has finished refreshing access token</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.MobileServiceJsonSerializerSettings SerializerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.MobileServiceJsonSerializerSettings SerializerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.SerializerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property SerializerSettings As MobileServiceJsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializerSettings : Microsoft.WindowsAzure.MobileServices.MobileServiceJsonSerializerSettings with get, set" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.SerializerSettings" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.MobileServices.IMobileServiceClient.SerializerSettings</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.MobileServiceJsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e236-221">Ruft ab oder legt die Einstellungen für die Serialisierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="1e236-221">Gets or sets the settings used for serialization.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SyncContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext SyncContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext SyncContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.MobileServiceClient.SyncContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SyncContext As IMobileServiceSyncContext" />
      <MemberSignature Language="F#" Value="member this.SyncContext : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceClient.SyncContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e236-222">Instanz von<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" /></span><span class="sxs-lookup"><span data-stu-id="1e236-222">Instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" /></span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
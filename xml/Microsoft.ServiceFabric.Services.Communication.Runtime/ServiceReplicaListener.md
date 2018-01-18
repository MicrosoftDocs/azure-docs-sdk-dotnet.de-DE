<Type Name="ServiceReplicaListener" FullName="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener">
  <TypeSignature Language="C#" Value="public sealed class ServiceReplicaListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceReplicaListener extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceReplicaListener" />
  <TypeSignature Language="F#" Value="type ServiceReplicaListener = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="29bce-101">Der Listener für die Kommunikation und die Eigenschaften für einen Zustandsbehafteten dienstreplikats darstellt.</span><span class="sxs-lookup"><span data-stu-id="29bce-101">Represents the communication listener and its properties for a Stateful Service replica.</span></span>
            <span data-ttu-id="29bce-102">Endpunkte, die vom Listener Kommunikation ausgegeben werden der Name des Listeners Kommunikation zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="29bce-102">Endpoints given out by the communication listener are associated with the name of the communication listener.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceReplicaListener (Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; createCommunicationListener, string name = &quot;&quot;, bool listenOnSecondary = false);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;class System.Fabric.StatefulServiceContext, class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; createCommunicationListener, string name, bool listenOnSecondary) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.#ctor(System.Func{System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener},System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createCommunicationListener As Func(Of StatefulServiceContext, ICommunicationListener), Optional name As String = &quot;&quot;, Optional listenOnSecondary As Boolean = false)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener : Func&lt;System.Fabric.StatefulServiceContext, Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; * string * bool -&gt; Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener" Usage="new Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener (createCommunicationListener, name, listenOnSecondary)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createCommunicationListener" Type="System.Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="listenOnSecondary" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="createCommunicationListener"><span data-ttu-id="29bce-103">Factorymethode zum Erstellen des Listeners Kommunikation</span><span class="sxs-lookup"><span data-stu-id="29bce-103">Factory method for creating the communication listener</span></span></param>
        <param name="name"><span data-ttu-id="29bce-104">Der Name des Listeners Kommunikation.</span><span class="sxs-lookup"><span data-stu-id="29bce-104">Name of the communication listener.</span></span> <span data-ttu-id="29bce-105">Dieser Parameter ist optional, wenn der Dienst nur eine Kommunikation Listener hat</span><span class="sxs-lookup"><span data-stu-id="29bce-105">This parameter is optional, if the service has only one communication listener</span></span></param>
        <param name="listenOnSecondary"><span data-ttu-id="29bce-106">Gibt an, ob der Listener Kommunikation muss geöffnet werden, wenn das Replikat aktive sekundäre Datenbank wird.</span><span class="sxs-lookup"><span data-stu-id="29bce-106">Specifies if the communication listener needs to be opened when the replica becomes Active secondary.</span></span> <span data-ttu-id="29bce-107">Dieser Parameter ist optional</span><span class="sxs-lookup"><span data-stu-id="29bce-107">THis parameter is optional</span></span></param>
        <summary>
            <span data-ttu-id="29bce-108">Erstellt die ServiceReplicaListener</span><span class="sxs-lookup"><span data-stu-id="29bce-108">Creates the ServiceReplicaListener</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCommunicationListener">
      <MemberSignature Language="C#" Value="public Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; CreateCommunicationListener { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;class System.Fabric.StatefulServiceContext, class Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt; CreateCommunicationListener" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.CreateCommunicationListener" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreateCommunicationListener As Func(Of StatefulServiceContext, ICommunicationListener)" />
      <MemberSignature Language="F#" Value="member this.CreateCommunicationListener : Func&lt;System.Fabric.StatefulServiceContext, Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.CreateCommunicationListener" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Fabric.StatefulServiceContext,Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="29bce-109">Ruft die Factorymethode zum Erstellen des Listeners für die Kommunikation ab.</span><span class="sxs-lookup"><span data-stu-id="29bce-109">Gets the factory method for creating the communication listener.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="29bce-110">Die Factorymethode zum Erstellen des Listeners für die Kommunikation.</span><span class="sxs-lookup"><span data-stu-id="29bce-110">The factory method for creating the communication listener.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="29bce-111">Die Factory-Methode akzeptiert eine <see cref="T:System.Fabric.StatefulServiceContext" /> und gibt Kommunikation Listener implementieren <see cref="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />.</span><span class="sxs-lookup"><span data-stu-id="29bce-111">The factory method takes in a <see cref="T:System.Fabric.StatefulServiceContext" /> and returns communication listener implementing <see cref="T:Microsoft.ServiceFabric.Services.Communication.Runtime.ICommunicationListener" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultName">
      <MemberSignature Language="C#" Value="public const string DefaultName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string DefaultName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.DefaultName" />
      <MemberSignature Language="VB.NET" Value="Public Const DefaultName As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultName : string" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.DefaultName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="29bce-112">Der Standardname des Dienst-Replikat-Listeners.</span><span class="sxs-lookup"><span data-stu-id="29bce-112">The default name of the Service replica listener.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="29bce-113">Der Standardname des Dienst-Replikat-Listeners.</span><span class="sxs-lookup"><span data-stu-id="29bce-113">The default name of the Service replica listener.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListenOnSecondary">
      <MemberSignature Language="C#" Value="public bool ListenOnSecondary { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ListenOnSecondary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.ListenOnSecondary" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListenOnSecondary As Boolean" />
      <MemberSignature Language="F#" Value="member this.ListenOnSecondary : bool" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.ListenOnSecondary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="29bce-114">Ruft das Flag, das angibt, ob diese Kommunikation Listener geöffnet werden soll, wenn das Replikat wird ein <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />.</span><span class="sxs-lookup"><span data-stu-id="29bce-114">Gets the flag that indicates if this communication listener should be opened when the replica becomes an <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />.</span></span></para>
          <para><span data-ttu-id="29bce-115">Wenn dieses Elements auf "false" festgelegt ist, wird die Kommunikation Listener geöffnet, nur, wenn das Replikat wird <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span><span class="sxs-lookup"><span data-stu-id="29bce-115">When this member is false, the communication listener is opened only when the replica becomes <see cref="F:System.Fabric.ReplicaRole.Primary" />.</span></span></para>
          <para><span data-ttu-id="29bce-116">Der Standardwert ist <languageKeyword>false</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="29bce-116">The default value is <languageKeyword>false</languageKeyword>.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="29bce-117">Das Flag, das angibt, ob diese Kommunikation Listener geöffnet werden soll, wenn das Replikat ist <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />.</span><span class="sxs-lookup"><span data-stu-id="29bce-117">The flag that indicates if this communication listener should be opened when the replica is <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="29bce-118">Dieses Flag kann festgelegt werden, wenn das primäre Replikat ist ausgelastet und Lesevorgänge dienen und schreibt Sie effizient und die Anwendung Daten lesen, veraltete (jedoch konsistent) tolerieren kann, und klicken Sie dann die Daten vom sekundären Replikat gelesen werden können.</span><span class="sxs-lookup"><span data-stu-id="29bce-118">This flag can be set when the primary replica is too busy to serve reads and writes efficiently and the application can tolerate reading stale (but consistent) data, then data can be read from secondary replica.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.ServiceFabric.Services.Communication.Runtime.ServiceReplicaListener.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="29bce-119">Ruft den Namen des Listeners Kommunikation.</span><span class="sxs-lookup"><span data-stu-id="29bce-119">Gets the name of the communication listener.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="29bce-120">Der Name des Listeners Kommunikation.</span><span class="sxs-lookup"><span data-stu-id="29bce-120">The name of the communication listener.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
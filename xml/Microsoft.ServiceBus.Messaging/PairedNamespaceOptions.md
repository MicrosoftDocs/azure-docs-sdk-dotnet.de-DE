<Type Name="PairedNamespaceOptions" FullName="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions">
  <TypeSignature Language="C#" Value="public abstract class PairedNamespaceOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit PairedNamespaceOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class PairedNamespaceOptions" />
  <TypeSignature Language="F#" Value="type PairedNamespaceOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary><span data-ttu-id="f6a7b-101">Stellt die Optionen für den gepaarten Namespace für den Servicebus-messaging dar.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-101">Represents the options for the paired namespace for the service bus messaging.</span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PairedNamespaceOptions (Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, Microsoft.ServiceBus.Messaging.MessagingFactory secondaryMessagingFactory);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, class Microsoft.ServiceBus.Messaging.MessagingFactory secondaryMessagingFactory) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.#ctor(Microsoft.ServiceBus.NamespaceManager,Microsoft.ServiceBus.Messaging.MessagingFactory)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (secondaryNamespaceManager As NamespaceManager, secondaryMessagingFactory As MessagingFactory)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.PairedNamespaceOptions : Microsoft.ServiceBus.NamespaceManager * Microsoft.ServiceBus.Messaging.MessagingFactory -&gt; Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" Usage="new Microsoft.ServiceBus.Messaging.PairedNamespaceOptions (secondaryNamespaceManager, secondaryMessagingFactory)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secondaryNamespaceManager" Type="Microsoft.ServiceBus.NamespaceManager" />
        <Parameter Name="secondaryMessagingFactory" Type="Microsoft.ServiceBus.Messaging.MessagingFactory" />
      </Parameters>
      <Docs>
        <param name="secondaryNamespaceManager"><span data-ttu-id="f6a7b-102">Die sekundären Namespace-Manager.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-102">The secondary namespace manager.</span></span></param>
        <param name="secondaryMessagingFactory"><span data-ttu-id="f6a7b-103">Die sekundären messagingfactory paarweise zugeordneten Namespace zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-103">The secondary messaging factory associated with the paired namespace.</span></span></param>
        <summary><span data-ttu-id="f6a7b-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-104">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected PairedNamespaceOptions (Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, Microsoft.ServiceBus.Messaging.MessagingFactory secondaryMessagingFactory, TimeSpan failoverInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.NamespaceManager secondaryNamespaceManager, class Microsoft.ServiceBus.Messaging.MessagingFactory secondaryMessagingFactory, valuetype System.TimeSpan failoverInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.#ctor(Microsoft.ServiceBus.NamespaceManager,Microsoft.ServiceBus.Messaging.MessagingFactory,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (secondaryNamespaceManager As NamespaceManager, secondaryMessagingFactory As MessagingFactory, failoverInterval As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.PairedNamespaceOptions : Microsoft.ServiceBus.NamespaceManager * Microsoft.ServiceBus.Messaging.MessagingFactory * TimeSpan -&gt; Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" Usage="new Microsoft.ServiceBus.Messaging.PairedNamespaceOptions (secondaryNamespaceManager, secondaryMessagingFactory, failoverInterval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secondaryNamespaceManager" Type="Microsoft.ServiceBus.NamespaceManager" />
        <Parameter Name="secondaryMessagingFactory" Type="Microsoft.ServiceBus.Messaging.MessagingFactory" />
        <Parameter Name="failoverInterval" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="secondaryNamespaceManager"><span data-ttu-id="f6a7b-105">Die sekundären Namespace-Manager.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-105">The secondary namespace manager.</span></span></param>
        <param name="secondaryMessagingFactory"><span data-ttu-id="f6a7b-106">Die sekundären messagingfactory paarweise zugeordneten Namespace zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-106">The secondary messaging factory associated with the paired namespace.</span></span></param>
        <param name="failoverInterval"><span data-ttu-id="f6a7b-107">Die Nachricht <see cref="T:System.TimeSpan" /> Intervall Failover.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-107">The message <see cref="T:System.TimeSpan" /> interval failover.</span></span></param>
        <summary><span data-ttu-id="f6a7b-108">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-108">Initializes a new instance of the <see cref="T:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions" /> class.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClearPairing">
      <MemberSignature Language="C#" Value="protected internal virtual void ClearPairing ();" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig newslot virtual instance void ClearPairing() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.ClearPairing" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Overridable Sub ClearPairing ()" />
      <MemberSignature Language="F#" Value="abstract member ClearPairing : unit -&gt; unit&#xA;override this.ClearPairing : unit -&gt; unit" Usage="pairedNamespaceOptions.ClearPairing " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="f6a7b-109">Hat die Kopplung des gepaarte Namespaces.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-109">Dissolves the pairing of the paired namespace.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverInterval">
      <MemberSignature Language="C#" Value="public TimeSpan FailoverInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan FailoverInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.FailoverInterval" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailoverInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.FailoverInterval : TimeSpan" Usage="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.FailoverInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f6a7b-110">Ruft die Meldung ab <see cref="T:System.TimeSpan" /> Intervall Failover.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-110">Gets the message <see cref="T:System.TimeSpan" /> interval failover.</span></span></summary>
        <value><span data-ttu-id="f6a7b-111">Die Nachricht <see cref="T:System.TimeSpan" /> Intervall Failover.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-111">The message <see cref="T:System.TimeSpan" /> interval failover.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnNotifyPrimarySendResult">
      <MemberSignature Language="C#" Value="protected abstract void OnNotifyPrimarySendResult (string path, bool success);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnNotifyPrimarySendResult(string path, bool success) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.OnNotifyPrimarySendResult(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnNotifyPrimarySendResult (path As String, success As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member OnNotifyPrimarySendResult : string * bool -&gt; unit" Usage="pairedNamespaceOptions.OnNotifyPrimarySendResult (path, success)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="success" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="path"><span data-ttu-id="f6a7b-112">Die Zeichenfolge des Pfads.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-112">The string of the path.</span></span></param>
        <param name="success"><span data-ttu-id="f6a7b-113">"true", wenn die Ergebnisse erfolgreich senden; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="f6a7b-113">true if the results successfully send; otherwise, false.</span></span></param>
        <summary><span data-ttu-id="f6a7b-114">Benachrichtigt die primären messaging auf das Ergebnis zu senden.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-114">Notifies the primary messaging on sending the result.</span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryMessagingFactory">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingFactory SecondaryMessagingFactory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.MessagingFactory SecondaryMessagingFactory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.SecondaryMessagingFactory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryMessagingFactory As MessagingFactory" />
      <MemberSignature Language="F#" Value="member this.SecondaryMessagingFactory : Microsoft.ServiceBus.Messaging.MessagingFactory" Usage="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.SecondaryMessagingFactory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingFactory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f6a7b-115">Ruft die sekundäre messagingfactory paarweise zugeordneten Namespace zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-115">Gets the secondary messaging factory associated with the paired namespace.</span></span></summary>
        <value><span data-ttu-id="f6a7b-116">Die sekundären messagingfactory paarweise zugeordneten Namespace zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-116">The secondary messaging factory associated with the paired namespace.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryNamespaceManager">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.NamespaceManager SecondaryNamespaceManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.NamespaceManager SecondaryNamespaceManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.SecondaryNamespaceManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryNamespaceManager As NamespaceManager" />
      <MemberSignature Language="F#" Value="member this.SecondaryNamespaceManager : Microsoft.ServiceBus.NamespaceManager" Usage="Microsoft.ServiceBus.Messaging.PairedNamespaceOptions.SecondaryNamespaceManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.NamespaceManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="f6a7b-117">Ruft das Objekt ab, das Entitäten, z. B. Warteschlangen, Themen, Abonnements und Regeln im paarweise zugeordneten Namespace verwaltet.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-117">Gets the object that manages entities, such as queues, topics, subscriptions and rules in the paired namespace.</span></span></summary>
        <value><span data-ttu-id="f6a7b-118">Das Objekt, das Entitäten, z. B. Warteschlangen, Themen, Abonnements und Regeln im paarweise zugeordneten Namespace verwaltet.</span><span class="sxs-lookup"><span data-stu-id="f6a7b-118">The object that manages entities, such as queues, topics, subscriptions and rules in the paired namespace.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
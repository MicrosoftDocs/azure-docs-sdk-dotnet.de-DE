<Type Name="FabricRuntime" FullName="System.Fabric.FabricRuntime">
  <TypeSignature Language="C#" Value="public sealed class FabricRuntime : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed FabricRuntime extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricRuntime" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricRuntime&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type FabricRuntime = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para><span data-ttu-id="f3dcc-101">Können benutzerdefinierte Hosts erhalten ihre <see cref="T:System.Fabric.CodePackageActivationContext" />, auch auf den erforderlichen Dienst Factorys registrieren [ <see cref="T:System.Fabric.IStatelessServiceFactory" />, <see cref="T:System.Fabric.IStatefulServiceFactory" />, oder <see cref="T:System.Fabric.ServiceGroupFactory" />] oder direkt Diensttypen.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-101">Allows user created hosts to obtain their <see cref="T:System.Fabric.CodePackageActivationContext" />, well as to register the necessary service factories [ <see cref="T:System.Fabric.IStatelessServiceFactory" />, <see cref="T:System.Fabric.IStatefulServiceFactory" />, or <see cref="T:System.Fabric.ServiceGroupFactory" />] or service types directly.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Fabric.FabricRuntime Create ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.FabricRuntime Create() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.Create" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create () As FabricRuntime" />
      <MemberSignature Language="F#" Value="static member Create : unit -&gt; System.Fabric.FabricRuntime" Usage="System.Fabric.FabricRuntime.Create " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricRuntime</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="f3dcc-102">Erstellt die <see cref="T:System.Fabric.FabricRuntime" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-102">Creates the <see cref="T:System.Fabric.FabricRuntime" /> object.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="f3dcc-103">Ein neu erstelltes <see cref="T:System.Fabric.FabricRuntime" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-103">A newly created <see cref="T:System.Fabric.FabricRuntime" /> object.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static System.Fabric.FabricRuntime Create (Action fabricExitCallback);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.FabricRuntime Create(class System.Action fabricExitCallback) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.Create(System.Action)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Create (fabricExitCallback As Action) As FabricRuntime" />
      <MemberSignature Language="F#" Value="static member Create : Action -&gt; System.Fabric.FabricRuntime" Usage="System.Fabric.FabricRuntime.Create fabricExitCallback" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricRuntime</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fabricExitCallback" Type="System.Action" />
      </Parameters>
      <Docs>
        <param name="fabricExitCallback">
          <para><span data-ttu-id="f3dcc-104">Die Aktion, die ausgeführt werden, wenn die Laufzeit beendet wird oder beendet wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-104">The Action to be executed when the runtime exits or terminates.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3dcc-105">Erstellt die <see cref="T:System.Fabric.FabricRuntime" /> Objekt mit einer festgelegten Rückruffunktion, die ausgeführt wird, wenn die zugrunde liegenden Laufzeit beendet wird oder aus irgendeinem Grund beendet wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-105">Creates the <see cref="T:System.Fabric.FabricRuntime" /> object with a specified callback function which will be executed if the underlying runtime terminates or exits for any reason.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="f3dcc-106">Ein neu erstelltes <see cref="T:System.Fabric.FabricRuntime" />Objekt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-106">A newly created <see cref="T:System.Fabric.FabricRuntime" />object.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt; CreateAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricRuntime&gt; CreateAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.CreateAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;" Usage="System.Fabric.FabricRuntime.CreateAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="f3dcc-107">Die maximale Zeitdauer Service Fabric können diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-107">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="f3dcc-108">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-108">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="f3dcc-109">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-109">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="f3dcc-110">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-110">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3dcc-111">Erstellt die <see cref="T:System.Fabric.FabricRuntime" /> asynchron mit dem angegebenen Objekt <paramref name="timeout" /> und <paramref name="cancellationToken" />.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-111">Creates the <see cref="T:System.Fabric.FabricRuntime" /> object asynchronously with the specified <paramref name="timeout" /> and <paramref name="cancellationToken" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="f3dcc-112">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-112">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt; CreateAsync (Action fabricExitCallback, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricRuntime&gt; CreateAsync(class System.Action fabricExitCallback, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.CreateAsync(System.Action,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Action * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;" Usage="System.Fabric.FabricRuntime.CreateAsync (fabricExitCallback, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricRuntime&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fabricExitCallback" Type="System.Action" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="fabricExitCallback">
          <para><span data-ttu-id="f3dcc-113">Die Aktion, die ausgeführt werden, wenn die Laufzeit beendet wird oder beendet wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-113">The Action to be executed when the runtime exits or terminates.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="f3dcc-114">Die maximale Zeitdauer Service Fabric können diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-114">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="f3dcc-115">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-115">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="f3dcc-116">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-116">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="f3dcc-117">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-117">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3dcc-118">Erstellt die <see cref="T:System.Fabric.FabricRuntime" /> Objekt asynchron mit der angegebenen Rückruf-Funktion, die ausgeführt wird, wenn die zugrunde liegenden Laufzeit beendet wird oder aus irgendeinem Grund beendet <paramref name="timeout" />, und <paramref name="cancellationToken" />.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-118">Creates the <see cref="T:System.Fabric.FabricRuntime" /> object asynchronously with the specified callback function which will be executed if the underlying runtime terminates or exits for any reason, <paramref name="timeout" />, and <paramref name="cancellationToken" />.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="f3dcc-119">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-119">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="fabricRuntime.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="f3dcc-120">Verwirft die <see cref="T:System.Fabric.FabricRuntime" />.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-120">Disposes of the <see cref="T:System.Fabric.FabricRuntime" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActivationContext">
      <MemberSignature Language="C#" Value="public static System.Fabric.CodePackageActivationContext GetActivationContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.CodePackageActivationContext GetActivationContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetActivationContext" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetActivationContext () As CodePackageActivationContext" />
      <MemberSignature Language="F#" Value="static member GetActivationContext : unit -&gt; System.Fabric.CodePackageActivationContext" Usage="System.Fabric.FabricRuntime.GetActivationContext " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.CodePackageActivationContext</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="f3dcc-121">Ruft ab den aktuellen <see cref="T:System.Fabric.FabricRuntime" />des <see cref="T:System.Fabric.CodePackageActivationContext" />.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-121">Retrieves the current <see cref="T:System.Fabric.FabricRuntime" />’s <see cref="T:System.Fabric.CodePackageActivationContext" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="f3dcc-122">Der Aktivierungskontext.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-122">The activation context.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetActivationContextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.CodePackageActivationContext&gt; GetActivationContextAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.CodePackageActivationContext&gt; GetActivationContextAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetActivationContextAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetActivationContextAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.CodePackageActivationContext&gt;" Usage="System.Fabric.FabricRuntime.GetActivationContextAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.CodePackageActivationContext&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="f3dcc-123">Die maximale Zeitdauer wird Service Fabric, diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException zulassen</span><span class="sxs-lookup"><span data-stu-id="f3dcc-123">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="f3dcc-124">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-124">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="f3dcc-125">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-125">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="f3dcc-126">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-126">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3dcc-127">Ruft ab den aktuellen <see cref="T:System.Fabric.FabricRuntime" />des <see cref="T:System.Fabric.CodePackageActivationContext" /> asynchron mit dem angegebenen <paramref name="timeout" /> und <paramref name="cancellationToken" />.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-127">Retrieves the current <see cref="T:System.Fabric.FabricRuntime" />’s <see cref="T:System.Fabric.CodePackageActivationContext" /> asynchronously with the specified <paramref name="timeout" /> and <paramref name="cancellationToken" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="f3dcc-128">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-128">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeContext">
      <MemberSignature Language="C#" Value="public static System.Fabric.NodeContext GetNodeContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.NodeContext GetNodeContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetNodeContext" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetNodeContext () As NodeContext" />
      <MemberSignature Language="F#" Value="static member GetNodeContext : unit -&gt; System.Fabric.NodeContext" Usage="System.Fabric.FabricRuntime.GetNodeContext " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeContext</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="f3dcc-129">Ruft die Knoten Context-Objekt, das Informationen zu Fabric-Knoten enthält.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-129">Gets the Node Context object that contains information about Fabric Node.</span></span> </para>
        </summary>
        <returns>
          <para><span data-ttu-id="f3dcc-130">Der Knotenkontext.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-130">The node context.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNodeContextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.NodeContext&gt; GetNodeContextAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.NodeContext&gt; GetNodeContextAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.GetNodeContextAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetNodeContextAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.NodeContext&gt;" Usage="System.Fabric.FabricRuntime.GetNodeContextAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.NodeContext&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="f3dcc-131">Die maximale Zeitdauer wird Service Fabric, diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException zulassen</span><span class="sxs-lookup"><span data-stu-id="f3dcc-131">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="f3dcc-132">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-132">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="f3dcc-133">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-133">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="f3dcc-134">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-134">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3dcc-135">Ruft Knotenkontext von Fabric-Knoten asynchron mit Timeout und ein Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-135">Gets Node Context from Fabric Node asynchronously with timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="f3dcc-136">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-136">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceGroupFactory">
      <MemberSignature Language="C#" Value="public void RegisterServiceGroupFactory (string serviceGroupTypeName, System.Fabric.ServiceGroupFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterServiceGroupFactory(string serviceGroupTypeName, class System.Fabric.ServiceGroupFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceGroupFactory(System.String,System.Fabric.ServiceGroupFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterServiceGroupFactory (serviceGroupTypeName As String, factory As ServiceGroupFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceGroupFactory : string * System.Fabric.ServiceGroupFactory -&gt; unit" Usage="fabricRuntime.RegisterServiceGroupFactory (serviceGroupTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.ServiceGroupFactory" />
      </Parameters>
      <Docs>
        <param name="serviceGroupTypeName">
          <para><span data-ttu-id="f3dcc-137">Der Typname des Diensttyps Dienstgruppe (als Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="f3dcc-137">The type name of the ServiceGroup service type (as a string).</span></span>  <span data-ttu-id="f3dcc-138">Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateServiceGroup übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-138">This should match the type of the service group type as specified in the manifests and/or the CreateServiceGroup command.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="f3dcc-139">Die <see cref="T:System.Fabric.ServiceGroupFactory" /> können die den angegebenen Diensttyp Gruppe erstellen.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-139">The <see cref="T:System.Fabric.ServiceGroupFactory" /> which can create the specified service group type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3dcc-140">Registriert das angegebene <see cref="T:System.Fabric.ServiceGroupFactory" /> für den angegebenen Typ.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-140">Registers the specified <see cref="T:System.Fabric.ServiceGroupFactory" /> for the specified type.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceGroupFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterServiceGroupFactoryAsync (string serviceGroupTypeName, System.Fabric.ServiceGroupFactory factory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterServiceGroupFactoryAsync(string serviceGroupTypeName, class System.Fabric.ServiceGroupFactory factory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceGroupFactoryAsync(System.String,System.Fabric.ServiceGroupFactory,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceGroupFactoryAsync : string * System.Fabric.ServiceGroupFactory * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterServiceGroupFactoryAsync (serviceGroupTypeName, factory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.ServiceGroupFactory" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceGroupTypeName">
          <para><span data-ttu-id="f3dcc-141">Der Typname des Diensttyps Dienstgruppe (als Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="f3dcc-141">The type name of the ServiceGroup service type (as a string).</span></span>  <span data-ttu-id="f3dcc-142">Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateServiceGroup übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-142">This should match the type of the service group type as specified in the manifests and/or the CreateServiceGroup command.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="f3dcc-143">Die <see cref="T:System.Fabric.ServiceGroupFactory" /> können die den angegebenen Diensttyp Gruppe erstellen.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-143">The <see cref="T:System.Fabric.ServiceGroupFactory" /> which can create the specified service group type.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="f3dcc-144">Die maximale Zeitdauer Service Fabric können diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-144">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="f3dcc-145">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-145">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span> <span data-ttu-id="f3dcc-146">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-146">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="f3dcc-147">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-147">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3dcc-148">Asynchron registriert das angegebene <see cref="T:System.Fabric.ServiceGroupFactory" /> für den angegebenen Diensttyp des Gruppe mit dem angegebenen <paramref name="timeout" /> und <paramref name="cancellationToken" />.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-148">Asynchronously registers the specified <see cref="T:System.Fabric.ServiceGroupFactory" /> for the specified service group type with the specified <paramref name="timeout" /> and <paramref name="cancellationToken" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="f3dcc-149">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-149">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceType">
      <MemberSignature Language="C#" Value="public void RegisterServiceType (string serviceTypeName, Type serviceTypeImplementation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterServiceType(string serviceTypeName, class System.Type serviceTypeImplementation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceType(System.String,System.Type)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterServiceType (serviceTypeName As String, serviceTypeImplementation As Type)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceType : string * Type -&gt; unit" Usage="fabricRuntime.RegisterServiceType (serviceTypeName, serviceTypeImplementation)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceTypeImplementation" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="f3dcc-150">Der Typname des Diensttyps (als Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="f3dcc-150">The type name of the service type (as a string).</span></span>  <span data-ttu-id="f3dcc-151">Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateService übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-151">This should match the type of the service group type as specified in the manifests and/or the CreateService command.</span></span></para>
        </param>
        <param name="serviceTypeImplementation">
          <para><span data-ttu-id="f3dcc-152">Der qualifizierte Dienst Typ, der dem angegebenen implementiert <paramref name="serviceTypeName" />.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-152">The qualified service Type that implements the specified <paramref name="serviceTypeName" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3dcc-153">Ordnet die angegebene <paramref name="serviceTypeName" /> mit der tatsächlichen verwalteten Typ, die ihn implementiert.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-153">Associates the specified <paramref name="serviceTypeName" /> with the actual managed Type that implements it.</span></span> </para>
        </summary>
        <remarks>
          <para><span data-ttu-id="f3dcc-154">Beachten Sie, dass dieser Mechanismus für die Registrierung der Service-Typ nicht über eine benutzerdefinierte erfordert <see cref="T:System.Fabric.IStatelessServiceFactory" /> oder <see cref="T:System.Fabric.IStatefulServiceFactory" /> zum Zeitpunkt der Registrierung bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-154">Note that this mechanism for service type registration does not require a custom <see cref="T:System.Fabric.IStatelessServiceFactory" /> or <see cref="T:System.Fabric.IStatefulServiceFactory" /> to be provided at registration time.</span></span>  <span data-ttu-id="f3dcc-155">Service Fabric eine zur Laufzeit generiert und automatisch zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-155">Service Fabric will generate one at runtime and utilize it automatically.</span></span>  <span data-ttu-id="f3dcc-156">Wenn für eine benutzerdefinierte Implementierung der Factory erforderlich ist, können Sie implementieren <see cref="T:System.Fabric.IStatelessServiceFactory" /> oder <see cref="T:System.Fabric.IStatefulServiceFactory" /> , und geben Sie diese über die entsprechenden Factory Registrierungsmethoden (<see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" /> oder <see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />)</span><span class="sxs-lookup"><span data-stu-id="f3dcc-156">If there is a need for a custom implementation of the factory, you can implement <see cref="T:System.Fabric.IStatelessServiceFactory" /> or <see cref="T:System.Fabric.IStatefulServiceFactory" /> and then provide those via the corresponding factory registration methods (<see cref="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" /> or <see cref="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />)</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceTypeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterServiceTypeAsync (string serviceTypeName, Type serviceTypeImplementation, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterServiceTypeAsync(string serviceTypeName, class System.Type serviceTypeImplementation, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterServiceTypeAsync(System.String,System.Type,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceTypeAsync : string * Type * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterServiceTypeAsync (serviceTypeName, serviceTypeImplementation, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="serviceTypeImplementation" Type="System.Type" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="f3dcc-157">Der Typname des Diensttyps (als Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="f3dcc-157">The type name of the service type (as a string).</span></span>  <span data-ttu-id="f3dcc-158">Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateService übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-158">This should match the type of the service group type as specified in the manifests and/or the CreateService command.</span></span></para>
        </param>
        <param name="serviceTypeImplementation">
          <para><span data-ttu-id="f3dcc-159">Der qualifizierte Dienst Typ, der dem angegebenen implementiert <paramref name="serviceTypeName" />.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-159">The qualified service Type that implements the specified <paramref name="serviceTypeName" />.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="f3dcc-160">Die maximale Zeitdauer Service Fabric können diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-160">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="f3dcc-161">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-161">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="f3dcc-162">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-162">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="f3dcc-163">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-163">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3dcc-164">Ordnet asynchron mit dem tatsächlichen verwalteten Typ die, mit der angegebenen Implementierung, der angegebenen ServiceTypeName <paramref name="timeout" /> und<paramref name="cancellationToken" /></span><span class="sxs-lookup"><span data-stu-id="f3dcc-164">Asynchronously associates the specified serviceTypeName with the actual managed Type that implements it, with the specified <paramref name="timeout" /> and <paramref name="cancellationToken" /></span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="f3dcc-165">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-165">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatefulServiceFactory">
      <MemberSignature Language="C#" Value="public void RegisterStatefulServiceFactory (string serviceTypeName, System.Fabric.IStatefulServiceFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterStatefulServiceFactory(string serviceTypeName, class System.Fabric.IStatefulServiceFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactory(System.String,System.Fabric.IStatefulServiceFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterStatefulServiceFactory (serviceTypeName As String, factory As IStatefulServiceFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatefulServiceFactory : string * System.Fabric.IStatefulServiceFactory -&gt; unit" Usage="fabricRuntime.RegisterStatefulServiceFactory (serviceTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatefulServiceFactory" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="f3dcc-166">Der Typname des Diensttyps (als Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="f3dcc-166">The type name of the service type (as a string).</span></span>  <span data-ttu-id="f3dcc-167">Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateService übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-167">This should match the type of the service group type as specified in the manifests and/or the CreateService command.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="f3dcc-168">Die <see cref="T:System.Fabric.IStatefulServiceFactory" /> können die den angegebenen Typ erstellt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-168">The <see cref="T:System.Fabric.IStatefulServiceFactory" /> which can create the specified service type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3dcc-169">Registriert das angegebene <see cref="T:System.Fabric.IStatefulServiceFactory" /> für den angegebenen Diensttyp.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-169">Registers the specified <see cref="T:System.Fabric.IStatefulServiceFactory" /> for the specified service type.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatefulServiceFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterStatefulServiceFactoryAsync (string serviceTypeName, System.Fabric.IStatefulServiceFactory factory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterStatefulServiceFactoryAsync(string serviceTypeName, class System.Fabric.IStatefulServiceFactory factory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatefulServiceFactoryAsync(System.String,System.Fabric.IStatefulServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatefulServiceFactoryAsync : string * System.Fabric.IStatefulServiceFactory * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterStatefulServiceFactoryAsync (serviceTypeName, factory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatefulServiceFactory" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="f3dcc-170">Der Typname des Diensttyps (als Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="f3dcc-170">The type name of the service type (as a string).</span></span>  <span data-ttu-id="f3dcc-171">Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateService übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-171">This should match the type of the service group type as specified in the manifests and/or the CreateService command.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="f3dcc-172">Die <see cref="T:System.Fabric.IStatefulServiceFactory" /> können die den angegebenen Typ erstellt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-172">The <see cref="T:System.Fabric.IStatefulServiceFactory" /> which can create the specified service type.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="f3dcc-173">Die maximale Zeitdauer Service Fabric können diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-173">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="f3dcc-174">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-174">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="f3dcc-175">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-175">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="f3dcc-176">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-176">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3dcc-177">Registriert das angegebene <see cref="T:System.Fabric.IStatefulServiceFactory" /> für den angegebenen Typ mit dem angegebenen <paramref name="timeout" /> und <paramref name="cancellationToken" />.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-177">Registers the specified <see cref="T:System.Fabric.IStatefulServiceFactory" /> for the specified service type with the specified <paramref name="timeout" /> and <paramref name="cancellationToken" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="f3dcc-178">Die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-178">The representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatelessServiceFactory">
      <MemberSignature Language="C#" Value="public void RegisterStatelessServiceFactory (string serviceTypeName, System.Fabric.IStatelessServiceFactory factory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RegisterStatelessServiceFactory(string serviceTypeName, class System.Fabric.IStatelessServiceFactory factory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactory(System.String,System.Fabric.IStatelessServiceFactory)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RegisterStatelessServiceFactory (serviceTypeName As String, factory As IStatelessServiceFactory)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatelessServiceFactory : string * System.Fabric.IStatelessServiceFactory -&gt; unit" Usage="fabricRuntime.RegisterStatelessServiceFactory (serviceTypeName, factory)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatelessServiceFactory" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="f3dcc-179">Der Typname des Diensttyps (als Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="f3dcc-179">The type name of the service type (as a string).</span></span>  <span data-ttu-id="f3dcc-180">Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateService übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-180">This should match the type of the service group type as specified in the manifests and/or the CreateService command.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="f3dcc-181">Die <see cref="T:System.Fabric.IStatelessServiceFactory" /> können die den angegebenen Typ erstellt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-181">The <see cref="T:System.Fabric.IStatelessServiceFactory" /> which can create the specified service type.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3dcc-182">Registriert das angegebene <see cref="T:System.Fabric.IStatelessServiceFactory" /> für den angegebenen Diensttyp.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-182">Registers the specified <see cref="T:System.Fabric.IStatelessServiceFactory" /> for the specified service type.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterStatelessServiceFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RegisterStatelessServiceFactoryAsync (string serviceTypeName, System.Fabric.IStatelessServiceFactory factory, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RegisterStatelessServiceFactoryAsync(string serviceTypeName, class System.Fabric.IStatelessServiceFactory factory, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricRuntime.RegisterStatelessServiceFactoryAsync(System.String,System.Fabric.IStatelessServiceFactory,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterStatelessServiceFactoryAsync : string * System.Fabric.IStatelessServiceFactory * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="fabricRuntime.RegisterStatelessServiceFactoryAsync (serviceTypeName, factory, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="factory" Type="System.Fabric.IStatelessServiceFactory" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceTypeName">
          <para><span data-ttu-id="f3dcc-183">Der Typname des Diensttyps (als Zeichenfolge).</span><span class="sxs-lookup"><span data-stu-id="f3dcc-183">The type name of the service type (as a string).</span></span>  <span data-ttu-id="f3dcc-184">Dies sollte den Typ des Diensttyps Gruppe entsprechend den Angaben in den Manifesten und/oder Befehls CreateService übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-184">This should match the type of the service group type as specified in the manifests and/or the CreateService command.</span></span></para>
        </param>
        <param name="factory">
          <para><span data-ttu-id="f3dcc-185">Die <see cref="T:System.Fabric.IStatelessServiceFactory" /> können die den angegebenen Typ erstellt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-185">The <see cref="T:System.Fabric.IStatelessServiceFactory" /> which can create the specified service type.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="f3dcc-186">Die maximale Zeitdauer Service Fabric können diesen Vorgang, um den Vorgang fortzusetzen, vor der Rückgabe einer TimeoutException.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-186">The maximum amount of time Service Fabric will allow this operation to continue before returning a TimeoutException.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="f3dcc-187">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-187">The <see cref="T:System.Threading.CancellationToken" /> that the operation is observing.</span></span>  <span data-ttu-id="f3dcc-188">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-188">It can be used to send a notification that the operation should be canceled.</span></span>  <span data-ttu-id="f3dcc-189">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-189">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f3dcc-190">Asynchron registriert das angegebene <see cref="T:System.Fabric.IStatelessServiceFactory" /> für den angegebenen Diensttyp, mit dem angegebenen <paramref name="timeout" /> und<paramref name="cancellationToken" /></span><span class="sxs-lookup"><span data-stu-id="f3dcc-190">Asynchronously registers the specified <see cref="T:System.Fabric.IStatelessServiceFactory" /> for the specified service type, with the specified <paramref name="timeout" /> and <paramref name="cancellationToken" /></span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="f3dcc-191">Die Aufgabe, die den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3dcc-191">The task representing the asynchronous operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
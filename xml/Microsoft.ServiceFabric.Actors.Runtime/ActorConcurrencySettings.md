<Type Name="ActorConcurrencySettings" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings">
  <TypeSignature Language="C#" Value="public sealed class ActorConcurrencySettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ActorConcurrencySettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ActorConcurrencySettings" />
  <TypeSignature Language="F#" Value="type ActorConcurrencySettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="42b66-101">Stellt die Einstellungen zum Konfigurieren von Turn basierend Concurrency Sperre für Akteure.</span><span class="sxs-lookup"><span data-stu-id="42b66-101">Provides the settings to configure the turn based concurrency lock for actors.</span></span> <span data-ttu-id="42b66-102">Finden Sie eine Beschreibung der Parallelität in Akteure https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-actors-introduction aus.</span><span class="sxs-lookup"><span data-stu-id="42b66-102">See https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-actors-introduction for a description of concurrency in actors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorConcurrencySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="42b66-103">Initialisiert eine neue Instanz der ActorConcurrencySettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="42b66-103">Initializes a new instance of the ActorConcurrencySettings class.</span></span>
            
            <span data-ttu-id="42b66-104">Standardmäßig die <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.ReentrancyMode" /> ist <see cref="F:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode.LogicalCallContext" /> mit einem <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.LockTimeout" /> von 60 Sekunden</span><span class="sxs-lookup"><span data-stu-id="42b66-104">By default the <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.ReentrancyMode" /> is <see cref="F:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode.LogicalCallContext" /> with a <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.LockTimeout" /> of 60 seconds</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LockTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan LockTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LockTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.LockTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LockTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LockTimeout : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.LockTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42b66-105">Ruft ab oder legt das Timeout für die Reihe basierend Concurrency Sperre.</span><span class="sxs-lookup"><span data-stu-id="42b66-105">Gets or sets the timeout for the turn based concurrency lock.</span></span> <span data-ttu-id="42b66-106">Wenn die Laufzeit die Sperre zum Verteilen des Methodenaufrufs abrufen kann, löst sie die <see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" /> Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="42b66-106">If the runtime cannot acquire the lock to dispatch the method call, it will throw the <see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" /> exception.</span></span> <span data-ttu-id="42b66-107">Diese Ausnahme wird die logische Aufrufkette entladen und der Aufruf wird oben auf eine konfigurierte maximale Häufigkeit wiederholt wird.</span><span class="sxs-lookup"><span data-stu-id="42b66-107">This exception will unwind the logical call chain and the call will retried up to a configured maximum amount of times.</span></span>
            </summary>
        <value><span data-ttu-id="42b66-108">Timeout für die Reihe basierend Concurrency Sperre.</span><span class="sxs-lookup"><span data-stu-id="42b66-108">Timeout for the turn based concurrency lock.</span></span> <span data-ttu-id="42b66-109">Dies kann festgelegt werden, um <see cref="F:System.Threading.Timeout.InfiniteTimeSpan" /> an ewig warten.</span><span class="sxs-lookup"><span data-stu-id="42b66-109">This can be set to <see cref="F:System.Threading.Timeout.InfiniteTimeSpan" /> to specify waiting forever.</span></span></value>
        <remarks>
            <span data-ttu-id="42b66-110">Der tatsächliche Timeoutwert für die Sperre des Parallelität kann liegen, wie die Common Language Runtime den angegebenen Wert einem zufällig gewählten Zeitpunkt hinzugefügt wird.</span><span class="sxs-lookup"><span data-stu-id="42b66-110">The actual timeout value for the concurrency lock can be higher as the runtime will add a random interval to the supplied value.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReentrancyMode">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode ReentrancyMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode ReentrancyMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.ReentrancyMode" />
      <MemberSignature Language="VB.NET" Value="Public Property ReentrancyMode As ActorReentrancyMode" />
      <MemberSignature Language="F#" Value="member this.ReentrancyMode : Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode with get, set" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.ReentrancyMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42b66-111">Ruft ab, oder legt ihn fest Reentranz Modus für Akteur Methodenaufrufe.</span><span class="sxs-lookup"><span data-stu-id="42b66-111">Gets or sets Reentrancy mode for actor method calls.</span></span>
            </summary>
        <value>
          <span data-ttu-id="42b66-112"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode" />für die Akteur-Methodenaufrufe.</span><span class="sxs-lookup"><span data-stu-id="42b66-112"><see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode" /> for the actor method calls.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
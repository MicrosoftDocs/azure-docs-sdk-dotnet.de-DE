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
            Stellt die Einstellungen zum Konfigurieren von Turn basierend Concurrency Sperre für Akteure. Finden Sie eine Beschreibung der Parallelität in Akteure https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-actors-introduction aus.
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
            Initialisiert eine neue Instanz der ActorConcurrencySettings-Klasse.
            
            Standardmäßig die <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.ReentrancyMode" /> ist <see cref="F:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode.LogicalCallContext" /> mit einem <see cref="P:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings.LockTimeout" /> von 60 Sekunden
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
            Ruft ab oder legt das Timeout für die Reihe basierend Concurrency Sperre. Wenn die Laufzeit die Sperre zum Verteilen des Methodenaufrufs abrufen kann, löst sie die <see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" /> Ausnahme. Diese Ausnahme wird die logische Aufrufkette entladen und der Aufruf wird oben auf eine konfigurierte maximale Häufigkeit wiederholt wird.
            </summary>
        <value>Timeout für die Reihe basierend Concurrency Sperre. Dies kann festgelegt werden, um <see cref="F:System.Threading.Timeout.InfiniteTimeSpan" /> an ewig warten.</value>
        <remarks>
            Der tatsächliche Timeoutwert für die Sperre des Parallelität kann liegen, wie die Common Language Runtime den angegebenen Wert einem zufällig gewählten Zeitpunkt hinzugefügt wird.
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
            Ruft ab, oder legt ihn fest Reentranz Modus für Akteur Methodenaufrufe.
            </summary>
        <value>
          <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorReentrancyMode" />für die Akteur-Methodenaufrufe.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
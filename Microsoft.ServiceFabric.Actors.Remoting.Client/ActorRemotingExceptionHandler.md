<Type Name="ActorRemotingExceptionHandler" FullName="Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler">
  <TypeSignature Language="C#" Value="public class ActorRemotingExceptionHandler : Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActorRemotingExceptionHandler extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler" />
  <TypeSignature Language="VB.NET" Value="Public Class ActorRemotingExceptionHandler&#xA;Implements IExceptionHandler" />
  <TypeSignature Language="F#" Value="type ActorRemotingExceptionHandler = class&#xA;    interface IExceptionHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Diese Klasse bereitstellen, Behandlung von Ausnahmen, die bei der Kommunikation mit Service Fabric Akteure über Remote Akteur Schnittstellen gefunden wird.
            </summary>
    <remarks>
      <para>
                Dieser Ausnahmehandler behandelt Ausnahmen, die im Zusammenhang mit den folgenden Szenarien.
            </para>
      <list type="list">
        <item>
          <term>
                Doppelte Nachrichten:
            </term>
          <description>
            <para>
                Vorgänge für der Akteur werden vom Client basierend auf der Logik zur Ausnahmebehandlung wiederholt. Diese Ausnahmen stellen verschiedene Fehlerzustand Dienstfailover dar. Aus diesem Grund ist es möglich, dass die Akteure mit doppelten Nachrichten zu empfangen. Wenn eine doppelte Nachricht empfangen wird, während vorherige Nachricht von der Akteur verarbeitet wird, Common Language Runtime eine interne Ausnahme an den Client zurückzugeben. Anschließend wiederholt der Client den Vorgang, um das Ergebnis aus der Akteur abzurufen. Aus Sicht der Akteur doppelt vorhandenen Vorgang wird von den Clients ausgeführt werden, und er sollte es auf ähnliche Weise behandeln, als ob der Vorgang wurde bereits verarbeitet, und klicken Sie dann eine Nachricht traf doppelt ein. 
                </para>
            <para>
                Ausnahme im Zusammenhang mit doppelt vorhandenen Vorgang verarbeiteten erfolgt durch Rückgabe <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> aus der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> Methode.
                Die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> Eigenschaft von der <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> festgelegt ist auf "true", die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" /> Eigenschaft wird auf einen Zufallswert festgelegt, bis zu <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" /> und <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> -Eigenschaftensatz auf <see cref="F:System.Int32.MaxValue" />.
                </para>
          </description>
        </item>
        <item>
          <term>
            <see cref="T:Microsoft.ServiceFabric.Actors.ActorConcurrencyLockTimeoutException" />:
            </term>
          <description>
            <para>
                Vorgänge für die Akteure dokumentdienstrollen erfolgt mithilfe von eine Basis aktivieren Concurrency Sperre (<see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorConcurrencySettings" />), die logische Aufruf Kontext Grundlage Reentranz unterstützt. Im Falle der Vorgänge mit langer Akteur ist es möglich, dass der Erhalt dieser Sperre zu einem Timeout führen. Die Übernahme der Sperre können auch einem Timeout bei einem Deadlocksituationen (Akteur A und Akteur B miteinander fast zur selben Zeit aufrufen). 
                </para>
            <para>
                Die Ausnahme, die im Zusammenhang mit der Parallelität Sperrtimeout erfolgt durch Rückgabe <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> aus der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> Methode, wenn der Client den Vorgang nicht auf einen anderen Akteur ist.
                Die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> Eigenschaft von der <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> festgelegt ist auf "true", die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" /> Eigenschaft wird auf einen Zufallswert festgelegt, bis zu <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" /> und <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> -Eigenschaftensatz auf <see cref="F:System.Int32.MaxValue" />.
                </para>
            <para>
                Die Ausnahme, die im Zusammenhang mit der Parallelität Sperrtimeout erfolgt durch Rückgabe <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult" /> aus der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> -Methode, wenn der Client den Vorgang ausführt, einen anderen Akteur ist. In den Deadlocksituationen, die Dies ermöglicht eine Aufrufkette ganz entladen, zurück an den ursprünglichen Client und der Vorgang dann von dort wiederholt wird.
                </para>
          </description>
        </item>
      </list>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActorRemotingExceptionHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
                Instanziiert eine neue <see cref="T:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler" /> die Behandeln von Ausnahmen, die bei der Kommunikation mit Service Fabric Akteure über Remote Akteur Schnittstellen gefunden verwendet werden können.
                </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException">
      <MemberSignature Language="C#" Value="bool IExceptionHandler.TryHandleException (Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, out Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult result);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, [out] class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Actors.Remoting.Client.ActorRemotingExceptionHandler.Microsoft#ServiceFabric#Services#Communication#Client#IExceptionHandler#TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exceptionInformation" Type="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation" />
        <Parameter Name="retrySettings" Type="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings" />
        <Parameter Name="result" Type="Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="exceptionInformation">Informationen zur Ausnahme</param>
        <param name="retrySettings">Die Voreinstellungen des Vorgang wiederholen.</param>
        <param name="result">Ergebnis der Behandlung von Ausnahmen</param>
        <summary>
            Methode, die die Ausnahme überprüft und bestimmt, wie die Ausnahme behandelt werden kann. 
            </summary>
        <returns>"true", wenn die Ausnahme behandelt "false" ist, andernfalls</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
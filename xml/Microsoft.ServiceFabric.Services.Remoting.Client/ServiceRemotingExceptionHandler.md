<Type Name="ServiceRemotingExceptionHandler" FullName="Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler">
  <TypeSignature Language="C#" Value="public class ServiceRemotingExceptionHandler : Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceRemotingExceptionHandler extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceRemotingExceptionHandler&#xA;Implements IExceptionHandler" />
  <TypeSignature Language="F#" Value="type ServiceRemotingExceptionHandler = class&#xA;    interface IExceptionHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
            <span data-ttu-id="5e678-101">Ermöglicht die Behandlung von Ausnahmen, die bei der Kommunikation mit einem Service Fabric-Dienst über Remote Schnittstellen gefunden.</span><span class="sxs-lookup"><span data-stu-id="5e678-101">Provides handling of exceptions encountered in communicating with a service fabric service over remoted interfaces.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="5e678-102">Ausnahmen werden gemäß der Beschreibung weiter unten behandelt: <list type="table"> <item> <description> die folgenden Ausnahmen geben Dienstfailover. Diese Ausnahmen werden behandelt, wird durch zurückgeben <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> aus der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> Methode. Die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> Eigenschaft von der <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> auf "false" festgelegt ist die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" /> Eigenschaft wird auf einen Zufallswert festgelegt, bis zu <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnNonTransientErrors" /> und <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> -Eigenschaftensatz auf <see cref="F:System.Int32.MaxValue" />. <list type="bullet"> <item> <description> <see cref="T:System.Fabric.FabricNotPrimaryException" />wird das Zielreplikat <see cref="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica" />.</description></item><item><description><see cref="T:System.Fabric.FabricNotReadableException" /></description></item></list></description></item><item><description> Die folgenden Ausnahmen vorübergehende Fehler an, und behandelt wird durch zurückgeben <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> aus der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> Methode. Die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> Eigenschaft von der <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> festgelegt ist auf "true", die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" /> Eigenschaft wird auf einen Zufallswert festgelegt, bis zu <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" /> und <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> -Eigenschaftensatz auf <see cref="F:System.Int32.MaxValue" />.<list type="bullet"><item><description><see cref="T:System.Fabric.FabricTransientException" /></description></item></list></description></item></list></span><span class="sxs-lookup"><span data-stu-id="5e678-102">The exceptions are handled as per the description below: <list type="table"><item><description> The following exceptions indicate service failover. These exceptions are handled by returning <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> from the <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> method. The <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> property of the <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> is set to false, the <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />  property is set to a random value up to <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnNonTransientErrors" /> and <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> property is set to <see cref="F:System.Int32.MaxValue" />. <list type="bullet"><item><description><see cref="T:System.Fabric.FabricNotPrimaryException" />, when the target replica is <see cref="F:Microsoft.ServiceFabric.Services.Communication.Client.TargetReplicaSelector.PrimaryReplica" />.</description></item><item><description><see cref="T:System.Fabric.FabricNotReadableException" /></description></item></list></description></item><item><description> The following exceptions indicate transient error conditions and handled by returning <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> from the <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> method. The <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> property of the <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> is set to true, the <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" />  property is set to a random value up to <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" /> and <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> property is set to <see cref="F:System.Int32.MaxValue" />. <list type="bullet"><item><description><see cref="T:System.Fabric.FabricTransientException" /></description></item></list></description></item></list></span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingExceptionHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5e678-103">Erstellt eine ServiceRemotingExceptionHandler hat den Standardwert Ablaufverfolgungs-ID.</span><span class="sxs-lookup"><span data-stu-id="5e678-103">Constructs a ServiceRemotingExceptionHandler with a default trace ID.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceRemotingExceptionHandler (string traceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string traceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (traceId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler : string -&gt; Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler" Usage="new Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler traceId" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="traceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="traceId">
                <span data-ttu-id="5e678-104">Die ID, die bei der Diagnose ablaufverfolgungen dieser Komponente verwenden.</span><span class="sxs-lookup"><span data-stu-id="5e678-104">The ID to use in diagnostics traces from this component.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e678-105">Erstellt eine ServiceRemotingExceptionHandler mit einer angegebene Ablaufverfolgung-ID.</span><span class="sxs-lookup"><span data-stu-id="5e678-105">Constructs a ServiceRemotingExceptionHandler with a specified trace ID.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException">
      <MemberSignature Language="C#" Value="bool IExceptionHandler.TryHandleException (Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, out Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult result);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, [out] class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Client.ServiceRemotingExceptionHandler.Microsoft#ServiceFabric#Services#Communication#Client#IExceptionHandler#TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
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
        <param name="exceptionInformation"><span data-ttu-id="5e678-106">Die Informationen zur Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="5e678-106">The information about the exception.</span></span></param>
        <param name="retrySettings"><span data-ttu-id="5e678-107">Die Voreinstellungen des Vorgang wiederholen.</span><span class="sxs-lookup"><span data-stu-id="5e678-107">The operation retry preferences.</span></span></param>
        <param name="result"><span data-ttu-id="5e678-108">Das Ergebnis der Behandlung von Ausnahmen.</span><span class="sxs-lookup"><span data-stu-id="5e678-108">The result of the exception handling.</span></span></param>
        <summary>
            <span data-ttu-id="5e678-109">Die Ausnahme überprüft und bestimmt, wie die Ausnahme behandelt werden kann.</span><span class="sxs-lookup"><span data-stu-id="5e678-109">Examines the exception and determines how that exception can be handled.</span></span> 
            </summary>
        <returns><span data-ttu-id="5e678-110">"true", wenn die Ausnahme verarbeitet wird; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="5e678-110">true if the exception is handled; otherwise, false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="WcfExceptionHandler" FullName="Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler">
  <TypeSignature Language="C#" Value="public class WcfExceptionHandler : Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WcfExceptionHandler extends System.Object implements class Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler" />
  <TypeSignature Language="VB.NET" Value="Public Class WcfExceptionHandler&#xA;Implements IExceptionHandler" />
  <TypeSignature Language="F#" Value="type WcfExceptionHandler = class&#xA;    interface IExceptionHandler" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
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
            Behandlung von WCF-Ausnahmen, die gefunden, bei der Kommunikation mit einem Service Fabric-Dienst, der mithilfe von WCF Kommunikation Listener Grundlage dieser Klasse bereitzustellen.
            </summary>
    <remarks>
            Ausnahmen werden gemäß der Beschreibung weiter unten behandelt: <list type="table"> <item> <description> die folgenden Ausnahmen geben Dienstfailover. Diese Ausnahmen werden behandelt, wird durch zurückgeben <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> aus der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> Methode. Die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> Eigenschaft von der <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> auf "false" festgelegt ist die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" /> Eigenschaft wird auf einen Zufallswert festgelegt, bis zu <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnNonTransientErrors" /> und <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> -Eigenschaftensatz auf <see cref="F:System.Int32.MaxValue" />. <list type="bullet"><item><description><see cref="T:System.ServiceModel.EndpointNotFoundException" /></description></item><item><description><see cref="T:System.ServiceModel.CommunicationObjectAbortedException" /></description></item><item><description><see cref="T:System.ServiceModel.CommunicationObjectFaultedException" /></description></item><item><description><see cref="T:System.ObjectDisposedException" /></description></item><item><description><see cref="T:System.ServiceModel.ChannelTerminatedException" /></description></item></list></description></item><item><description>Die folgenden Ausnahmen vorübergehende Fehler an, und behandelt wird durch zurückgeben <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> aus der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> Methode. Die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> Eigenschaft von der <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> festgelegt ist auf "true", die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" /> Eigenschaft wird auf einen Zufallswert festgelegt, bis zu <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" /> und <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> -Eigenschaftensatz auf <see cref="F:System.Int32.MaxValue" />. <list type="bullet"><item><description><see cref="T:System.TimeoutException" /></description></item><item><description><see cref="T:System.ServiceModel.ServerTooBusyException" /></description></item></list></description></item><item><description>Die folgenden Ausnahmen geben Sie übereinstimmende Datentypen in der Bindung oder am Vertrag zwischen dem Client und den Dienst an. Diese Ausnahmen werden behandelt, wird durch zurückgeben <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult" /> aus der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> Methode. <list type="bullet"><item><description><see cref="T:System.ServiceModel.ActionNotSupportedException" /></description></item><item><description><see cref="T:System.ServiceModel.AddressAccessDeniedException" /></description></item><item><description><see cref="T:System.ServiceModel.Security.SecurityAccessDeniedException" /></description></item></list></description></item><item><description>Die folgenden Ausnahmen sind geben einen Fehler vom Dienst an. Durch zurückgeben mit ihnen umgegangen <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingThrowResult" /> aus der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> Methode. <list type="bullet"><item><description><see cref="T:System.ServiceModel.FaultException" /></description></item></list></description></item><item><description>Alle anderen Ausnahmen werden <see cref="T:System.ServiceModel.CommunicationException" />, aber nicht <see cref="T:System.ServiceModel.FaultException" /> umgegangen wird durch zurückgeben <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> aus der <see cref="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" /> Methode. Die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.IsTransient" /> Eigenschaft von der <see cref="T:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult" /> festgelegt ist auf "true", die <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.RetryDelay" /> Eigenschaft wird auf einen Zufallswert festgelegt, bis zu <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.MaxRetryBackoffIntervalOnTransientErrors" /> und <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingRetryResult.MaxRetryCount" /> -Eigenschaftensatz auf <see cref="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings.DefaultMaxRetryCount" />.</description></item></list></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WcfExceptionHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der WcfExceptionHandler-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException">
      <MemberSignature Language="C#" Value="bool IExceptionHandler.TryHandleException (Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, out Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult result);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance bool Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, [out] class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Wcf.Client.WcfExceptionHandler.Microsoft#ServiceFabric#Services#Communication#Client#IExceptionHandler#TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Wcf</AssemblyName>
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
<Type Name="IExceptionHandler" FullName="Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler">
  <TypeSignature Language="C#" Value="public interface IExceptionHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IExceptionHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IExceptionHandler" />
  <TypeSignature Language="F#" Value="type IExceptionHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Definiert die Schnittstelle für die Ausnahmebehandlung bei der Kommunikation mit Service Fabric-Dienste gefunden. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TryHandleException">
      <MemberSignature Language="C#" Value="public bool TryHandleException (Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, out Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult result);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryHandleException(class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation exceptionInformation, class Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings retrySettings, [out] class Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult&amp; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.IExceptionHandler.TryHandleException(Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation,Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings,Microsoft.ServiceFabric.Services.Communication.Client.ExceptionHandlingResult@)" />
      <MemberSignature Language="F#" Value="abstract member TryHandleException : Microsoft.ServiceFabric.Services.Communication.Client.ExceptionInformation * Microsoft.ServiceFabric.Services.Communication.Client.OperationRetrySettings *  -&gt; bool" Usage="iExceptionHandler.TryHandleException (exceptionInformation, retrySettings, result)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
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
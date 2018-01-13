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
            <span data-ttu-id="1dd45-101">Definiert die Schnittstelle für die Ausnahmebehandlung bei der Kommunikation mit Service Fabric-Dienste gefunden.</span><span class="sxs-lookup"><span data-stu-id="1dd45-101">Defines the interface for handling the exceptions encountered in communicating with service fabric services.</span></span> 
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
        <param name="exceptionInformation"><span data-ttu-id="1dd45-102">Informationen zur Ausnahme</span><span class="sxs-lookup"><span data-stu-id="1dd45-102">Information about the exception</span></span></param>
        <param name="retrySettings"><span data-ttu-id="1dd45-103">Die Voreinstellungen des Vorgang wiederholen.</span><span class="sxs-lookup"><span data-stu-id="1dd45-103">The operation retry preferences.</span></span></param>
        <param name="result"><span data-ttu-id="1dd45-104">Ergebnis der Behandlung von Ausnahmen</span><span class="sxs-lookup"><span data-stu-id="1dd45-104">Result of the exception handling</span></span></param>
        <summary>
            <span data-ttu-id="1dd45-105">Methode, die die Ausnahme überprüft und bestimmt, wie die Ausnahme behandelt werden kann.</span><span class="sxs-lookup"><span data-stu-id="1dd45-105">Method that examines the exception and determines how that exception can be handled.</span></span> 
            </summary>
        <returns><span data-ttu-id="1dd45-106">"true", wenn die Ausnahme behandelt "false" ist, andernfalls</span><span class="sxs-lookup"><span data-stu-id="1dd45-106">true if the exception is handled, false otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
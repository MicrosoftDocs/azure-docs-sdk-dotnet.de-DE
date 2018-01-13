<Type Name="ResponseInterceptor+BatchResponseInterceptHandler" FullName="Microsoft.Azure.Batch.Protocol.ResponseInterceptor+BatchResponseInterceptHandler">
  <TypeSignature Language="C#" Value="public delegate System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IAzureOperationResponse&gt; ResponseInterceptor.BatchResponseInterceptHandler(IAzureOperationResponse response, IBatchRequest request);" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed ResponseInterceptor/BatchResponseInterceptHandler extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.ResponseInterceptor.BatchResponseInterceptHandler" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function ResponseInterceptor.BatchResponseInterceptHandler(response As IAzureOperationResponse, request As IBatchRequest) As Task(Of IAzureOperationResponse) " />
  <TypeSignature Language="F#" Value="type ResponseInterceptor.BatchResponseInterceptHandler = delegate of IAzureOperationResponse * IBatchRequest -&gt; Task&lt;IAzureOperationResponse&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="response" Type="Microsoft.Rest.Azure.IAzureOperationResponse" />
    <Parameter Name="request" Type="Microsoft.Azure.Batch.Protocol.IBatchRequest" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IAzureOperationResponse&gt;</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="response">Die Antwort überprüft und optional geändert werden.</param>
    <param name="request">Die Anforderung an die die <paramref name="response" /> ist eine Antwort.</param>
    <summary>
            Ein Rückruf, der überprüfen und eine BatchResponse ändern kann.
            </summary>
    <returns>To be added.</returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>
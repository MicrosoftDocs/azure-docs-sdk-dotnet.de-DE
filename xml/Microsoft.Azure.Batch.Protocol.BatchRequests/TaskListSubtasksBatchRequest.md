<Type Name="TaskListSubtasksBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListSubtasksBatchRequest">
  <TypeSignature Language="C#" Value="public class TaskListSubtasksBatchRequest : Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskListSubtasksBatchRequest extends Microsoft.Azure.Batch.Protocol.BatchRequest`2&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions, class Microsoft.Rest.Azure.AzureOperationResponse`2&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult, class Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListSubtasksBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskListSubtasksBatchRequest&#xA;Inherits BatchRequest(Of TaskListSubtasksOptions, AzureOperationResponse(Of CloudTaskListSubtasksResult, TaskListSubtasksHeaders))" />
  <TypeSignature Language="F#" Value="type TaskListSubtasksBatchRequest = class&#xA;    inherit BatchRequest&lt;TaskListSubtasksOptions, AzureOperationResponse&lt;CloudTaskListSubtasksResult, TaskListSubtasksHeaders&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.Protocol.BatchRequest&lt;Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions,Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="TOptions">Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksOptions</BaseTypeArgument>
      <BaseTypeArgument TypeParamName="TResponse">Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Batch.Protocol.Models.CloudTaskListSubtasksResult,Microsoft.Azure.Batch.Protocol.Models.TaskListSubtasksHeaders&gt;</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="725af-101">Ein <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> für den TaskListSubtasks-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="725af-101">An <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" /> for the TaskListSubtasks operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskListSubtasksBatchRequest (Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient serviceClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListSubtasksBatchRequest.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListSubtasksBatchRequest : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListSubtasksBatchRequest" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListSubtasksBatchRequest (serviceClient, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceClient"><span data-ttu-id="725af-102">Der Dienstclient verwendet.</span><span class="sxs-lookup"><span data-stu-id="725af-102">The service client to use.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="725af-103">Ein <see cref="T:System.Threading.CancellationToken" /> Steuerung der Lebensdauer der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="725af-103">A <see cref="T:System.Threading.CancellationToken" /> controlling the request lifetime.</span></span></param>
        <summary>
            <span data-ttu-id="725af-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListSubtasksBatchRequest" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="725af-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequests.TaskListSubtasksBatchRequest" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
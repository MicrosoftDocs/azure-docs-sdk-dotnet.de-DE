<Type Name="AzureTableSink" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureTableSink">
  <TypeSignature Language="C#" Value="public class AzureTableSink : Microsoft.Azure.Management.DataFactories.Models.CopySink" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureTableSink extends Microsoft.Azure.Management.DataFactories.Models.CopySink" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureTableSink" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureTableSink&#xA;Inherits CopySink" />
  <TypeSignature Language="F#" Value="type AzureTableSink = class&#xA;    inherit CopySink" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.CopySink</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7cf8a-101">Eine Azure-Tabelle-Senke kopieren-Aktivität.</span><span class="sxs-lookup"><span data-stu-id="7cf8a-101">A copy activity Azure table sink.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableSink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureTableSink.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureTableSink (int writeBatchSize, TimeSpan writeBatchTimeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 writeBatchSize, valuetype System.TimeSpan writeBatchTimeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.AzureTableSink.#ctor(System.Int32,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (writeBatchSize As Integer, writeBatchTimeout As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactories.Models.AzureTableSink : int * TimeSpan -&gt; Microsoft.Azure.Management.DataFactories.Models.AzureTableSink" Usage="new Microsoft.Azure.Management.DataFactories.Models.AzureTableSink (writeBatchSize, writeBatchTimeout)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="writeBatchSize" Type="System.Int32" />
        <Parameter Name="writeBatchTimeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="writeBatchSize">To be added.</param>
        <param name="writeBatchTimeout">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableDefaultPartitionKeyValue">
      <MemberSignature Language="C#" Value="public string AzureTableDefaultPartitionKeyValue { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureTableDefaultPartitionKeyValue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureTableSink.AzureTableDefaultPartitionKeyValue" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableDefaultPartitionKeyValue As String" />
      <MemberSignature Language="F#" Value="member this.AzureTableDefaultPartitionKeyValue : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureTableSink.AzureTableDefaultPartitionKeyValue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7cf8a-102">Azure-Tabelle standardmäßiger partitionsschlüsselwert.</span><span class="sxs-lookup"><span data-stu-id="7cf8a-102">Azure table default partition key value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableInsertType">
      <MemberSignature Language="C#" Value="public string AzureTableInsertType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureTableInsertType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureTableSink.AzureTableInsertType" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableInsertType As String" />
      <MemberSignature Language="F#" Value="member this.AzureTableInsertType : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureTableSink.AzureTableInsertType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7cf8a-103">Typ des Azure-Tabelle einfügen.</span><span class="sxs-lookup"><span data-stu-id="7cf8a-103">Azure table insert type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTablePartitionKeyName">
      <MemberSignature Language="C#" Value="public string AzureTablePartitionKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureTablePartitionKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureTableSink.AzureTablePartitionKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTablePartitionKeyName As String" />
      <MemberSignature Language="F#" Value="member this.AzureTablePartitionKeyName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureTableSink.AzureTablePartitionKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7cf8a-104">Azure-Tabelle Partition der Schlüsselname.</span><span class="sxs-lookup"><span data-stu-id="7cf8a-104">Azure table partition key name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableRowKeyName">
      <MemberSignature Language="C#" Value="public string AzureTableRowKeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureTableRowKeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.AzureTableSink.AzureTableRowKeyName" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureTableRowKeyName As String" />
      <MemberSignature Language="F#" Value="member this.AzureTableRowKeyName : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureTableSink.AzureTableRowKeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7cf8a-105">Azure-Tabelle Zeile der Schlüsselname.</span><span class="sxs-lookup"><span data-stu-id="7cf8a-105">Azure table row key name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="CheckpointFrequency" FullName="Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency">
  <TypeSignature Language="C#" Value="public class CheckpointFrequency" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CheckpointFrequency extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency" />
  <TypeSignature Language="VB.NET" Value="Public Class CheckpointFrequency" />
  <TypeSignature Language="F#" Value="type CheckpointFrequency = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.17.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a6800-101">Gibt die Häufigkeit der leaseereignis.</span><span class="sxs-lookup"><span data-stu-id="a6800-101">Specifies the frequency of lease event.</span></span> <span data-ttu-id="a6800-102">Das Ereignis wird ausgelöst, wenn eine der Bedingungen erfüllt wird.</span><span class="sxs-lookup"><span data-stu-id="a6800-102">The event will trigger when either of conditions is satisfied.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckpointFrequency ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessedDocumentCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ProcessedDocumentCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ProcessedDocumentCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency.ProcessedDocumentCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessedDocumentCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ProcessedDocumentCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency.ProcessedDocumentCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6800-103">Ruft ab oder legt den Wert, der Prüfpunkt alle angegebenen Anzahl der Dokumente angibt.</span><span class="sxs-lookup"><span data-stu-id="a6800-103">Gets or sets the value that specifies to checkpoint every specified number of docs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; TimeInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; TimeInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency.TimeInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.TimeInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency.TimeInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6800-104">Ruft ab oder legt den Wert, der Prüfpunkt jeder angegebenen Zeitintervall angibt.</span><span class="sxs-lookup"><span data-stu-id="a6800-104">Gets or sets the value that specifies to checkpoint every specified time interval.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
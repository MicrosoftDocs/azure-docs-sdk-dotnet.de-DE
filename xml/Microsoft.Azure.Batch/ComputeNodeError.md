<Type Name="ComputeNodeError" FullName="Microsoft.Azure.Batch.ComputeNodeError">
  <TypeSignature Language="C#" Value="public class ComputeNodeError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ComputeNodeError" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeError" />
  <TypeSignature Language="F#" Value="type ComputeNodeError = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cec0c-101">Ein Fehler durch einen Azure Batch-Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="cec0c-101">An error encountered by an Azure Batch compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeError.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.Batch.ComputeNodeError.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cec0c-102">Ruft einen Code für den Fehler der Compute-Knoten.</span><span class="sxs-lookup"><span data-stu-id="cec0c-102">Gets a code for the compute node error.</span></span> <span data-ttu-id="cec0c-103">Finden Sie unter <see cref="T:Microsoft.Azure.Batch.Common.BatchErrorCodeStrings" /> mögliche Werte.</span><span class="sxs-lookup"><span data-stu-id="cec0c-103">See <see cref="T:Microsoft.Azure.Batch.Common.BatchErrorCodeStrings" /> for possible values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorDetails">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NameValuePair&gt; ErrorDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.NameValuePair&gt; ErrorDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeError.ErrorDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorDetails As IReadOnlyList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.ErrorDetails : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NameValuePair&gt;" Usage="Microsoft.Azure.Batch.ComputeNodeError.ErrorDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cec0c-104">Ruft eine Liste der zusätzlichen Fehlerinformationen im Zusammenhang mit der Compute-Knoten-Fehler ab.</span><span class="sxs-lookup"><span data-stu-id="cec0c-104">Gets a list of additional error details related to the compute node error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ComputeNodeError.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Batch.ComputeNodeError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cec0c-105">Ruft eine Meldung Compute Knoten, für die Anzeige in einer Benutzeroberfläche geeignet sein soll.</span><span class="sxs-lookup"><span data-stu-id="cec0c-105">Gets a message describing the compute node error, intended to be suitable for display in a user interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
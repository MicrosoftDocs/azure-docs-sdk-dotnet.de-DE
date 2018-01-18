<Type Name="BatchException" FullName="Microsoft.Azure.Batch.Common.BatchException">
  <TypeSignature Language="C#" Value="public class BatchException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.BatchException" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type BatchException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3bc97-101">Repräsentiert eine Ausnahme für den Windows Azure Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="3bc97-101">Represents an exception for the Windows Azure Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BatchException (Microsoft.Azure.Batch.Common.RequestInformation requestInformation, string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Common.RequestInformation requestInformation, string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.BatchException.#ctor(Microsoft.Azure.Batch.Common.RequestInformation,System.String,System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Common.BatchException : Microsoft.Azure.Batch.Common.RequestInformation * string * Exception -&gt; Microsoft.Azure.Batch.Common.BatchException" Usage="new Microsoft.Azure.Batch.Common.BatchException (requestInformation, message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="requestInformation" Type="Microsoft.Azure.Batch.Common.RequestInformation" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="requestInformation"><span data-ttu-id="3bc97-102">Ein <see cref="P:Microsoft.Azure.Batch.Common.BatchException.RequestInformation" /> Objekt, das Details der Anforderung enthält.</span><span class="sxs-lookup"><span data-stu-id="3bc97-102">A <see cref="P:Microsoft.Azure.Batch.Common.BatchException.RequestInformation" /> object containing details about the request.</span></span></param>
        <param name="message"><span data-ttu-id="3bc97-103">Die Ausnahmemeldung.</span><span class="sxs-lookup"><span data-stu-id="3bc97-103">The exception message.</span></span></param>
        <param name="inner"><span data-ttu-id="3bc97-104">Die innere Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="3bc97-104">The inner exception.</span></span></param>
        <summary>
            <span data-ttu-id="3bc97-105">Initialisiert mit den angegebenen Parametern eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Common.BatchException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3bc97-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Common.BatchException" /> class by using the specified parameters.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.RequestInformation RequestInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Common.RequestInformation RequestInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.BatchException.RequestInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestInformation As RequestInformation" />
      <MemberSignature Language="F#" Value="member this.RequestInformation : Microsoft.Azure.Batch.Common.RequestInformation" Usage="Microsoft.Azure.Batch.Common.BatchException.RequestInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.RequestInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3bc97-106">Ruft Informationen zur Anforderung der fehlgeschlagenen ab.</span><span class="sxs-lookup"><span data-stu-id="3bc97-106">Gets information about the request which failed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.BatchException.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="batchException.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3bc97-107">Generiert eine Zeichenfolge, die die Ausnahme beschreibt.</span><span class="sxs-lookup"><span data-stu-id="3bc97-107">Generates a string which describes the exception.</span></span>
            </summary>
        <returns><span data-ttu-id="3bc97-108">Eine Zeichenfolge, die die Ausnahme darstellt.</span><span class="sxs-lookup"><span data-stu-id="3bc97-108">A string that represents the exception.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
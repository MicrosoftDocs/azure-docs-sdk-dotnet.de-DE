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
            Repräsentiert eine Ausnahme für den Windows Azure Batch-Dienst.
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
        <param name="requestInformation">Ein <see cref="P:Microsoft.Azure.Batch.Common.BatchException.RequestInformation" /> Objekt, das Details der Anforderung enthält.</param>
        <param name="message">Die Ausnahmemeldung.</param>
        <param name="inner">Die innere Ausnahme.</param>
        <summary>
            Initialisiert mit den angegebenen Parametern eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Common.BatchException" />-Klasse.
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
            Ruft Informationen zur Anforderung der fehlgeschlagenen ab.
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
            Generiert eine Zeichenfolge, die die Ausnahme beschreibt.
            </summary>
        <returns>Eine Zeichenfolge, die die Ausnahme darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="BatchError" FullName="Microsoft.Azure.Batch.BatchError">
  <TypeSignature Language="C#" Value="public class BatchError" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchError extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.BatchError" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchError" />
  <TypeSignature Language="F#" Value="type BatchError = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Ein Fehler von der Azure Batch-Dienst empfangen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public string Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchError.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As String" />
      <MemberSignature Language="F#" Value="member this.Code : string" Usage="Microsoft.Azure.Batch.BatchError.Code" />
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
            Ruft einen Code für den Fehler ab. Finden Sie unter <see cref="T:Microsoft.Azure.Batch.Common.BatchErrorCodeStrings" /> mögliche Werte.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ErrorMessage Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ErrorMessage Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchError.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As ErrorMessage" />
      <MemberSignature Language="F#" Value="member this.Message : Microsoft.Azure.Batch.ErrorMessage" Usage="Microsoft.Azure.Batch.BatchError.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ErrorMessage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine Meldung, die Beschreibung des Fehlers, der für die Anzeige in einer Benutzeroberfläche geeignet sein soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.BatchErrorDetail&gt; Values { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.BatchErrorDetail&gt; Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchError.Values" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Values As IReadOnlyList(Of BatchErrorDetail)" />
      <MemberSignature Language="F#" Value="member this.Values : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.BatchErrorDetail&gt;" Usage="Microsoft.Azure.Batch.BatchError.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.BatchErrorDetail&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine Auflistung von Schlüssel-Wert-Paaren, die zusätzliche Informationen über den Fehler enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
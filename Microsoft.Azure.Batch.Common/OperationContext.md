<Type Name="OperationContext" FullName="Microsoft.Azure.Batch.Common.OperationContext">
  <TypeSignature Language="C#" Value="public sealed class OperationContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit OperationContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.OperationContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class OperationContext" />
  <TypeSignature Language="F#" Value="type OperationContext = class" />
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
            Stellt den Kontext für eine Anforderung an den Batch-Dienst und bietet zusätzliche Informationen über seine Ausführung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.OperationContext.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Common.OperationContext" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestResults">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Common.RequestResult&gt; RequestResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Common.RequestResult&gt; RequestResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.OperationContext.RequestResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestResults As IList(Of RequestResult)" />
      <MemberSignature Language="F#" Value="member this.RequestResults : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Common.RequestResult&gt;" Usage="Microsoft.Azure.Batch.Common.OperationContext.RequestResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Common.RequestResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Anforderungsergebnisse für den aktuellen Vorgang.  Jede <see cref="T:Microsoft.Azure.Batch.Common.RequestResult" /> entspricht einer Anforderung an den Server gesendet.  Es gibt möglicherweise mehr als ein Element in dieser Liste bei Wiederholungen.
            </summary>
        <value>Ein <see cref="T:System.Collections.IList" /> Objekt, das enthält <see cref="T:Microsoft.Azure.Batch.Common.RequestResult" /> Objekte, die die vom aktuellen Vorgang erstellten Anforderungsergebnisse darstellen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
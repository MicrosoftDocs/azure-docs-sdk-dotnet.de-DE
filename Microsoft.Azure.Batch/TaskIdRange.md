<Type Name="TaskIdRange" FullName="Microsoft.Azure.Batch.TaskIdRange">
  <TypeSignature Language="C#" Value="public class TaskIdRange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskIdRange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskIdRange" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskIdRange" />
  <TypeSignature Language="F#" Value="type TaskIdRange = class&#xA;    interface ITransportObjectProvider&lt;TaskIdRange&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Einen Bereich von Aufgaben-Ids, die eine <see cref="T:Microsoft.Azure.Batch.CloudTask" /> abhängig. Alle Aufgaben-Ids im Bereich müssen erfolgreich abgeschlossen, bevor der abhängige Task geplant werden kann.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskIdRange (int start, int end);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 start, int32 end) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskIdRange.#ctor(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (start As Integer, end As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.TaskIdRange : int * int -&gt; Microsoft.Azure.Batch.TaskIdRange" Usage="new Microsoft.Azure.Batch.TaskIdRange (start, end)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="System.Int32" />
        <Parameter Name="end" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="start">Der erste Task-Id im Bereich.</param>
        <param name="end">Die letzte Task-Id im Bereich.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.TaskIdRange" />-Klasse.
            </summary>
        <remarks>
            Bereiche sind inklusiv. Z. B. wenn eine Aufgabe sich nach einem Bereich mit 8 Start und Ende 10 richtet dann tasks "8", muss "9" und "10" abschließen, bevor die Aufgabe geplant werden kann.
            </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <paramref name="start" /> oder <paramref name="end" /> ist ein negativer Wert.</exception>
        <exception cref="T:System.ArgumentException">
          <paramref name="end" /> ist kleiner als <paramref name="start" />.</exception>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public int End { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskIdRange.End" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property End As Integer" />
      <MemberSignature Language="F#" Value="member this.End : int" Usage="Microsoft.Azure.Batch.TaskIdRange.End" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den letzten Task-Id in den Bereich ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Bereiche sind inklusiv. Z. B. wenn ein Task auf einen Bereich mit der End-12 abhängig ist, muss dann Aufgabe "12" abschließen, bevor die Aufgabe geplant werden kann.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public int Start { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskIdRange.Start" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Start As Integer" />
      <MemberSignature Language="F#" Value="member this.Start : int" Usage="Microsoft.Azure.Batch.TaskIdRange.Start" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den ersten Task-Id in den Bereich ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Bereiche sind inklusiv. Z. B. wenn ein Task auf einen Bereich mit 8 Starten abhängig ist, muss dann Aufgabe "8" abschließen, bevor die Aufgabe geplant werden kann.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
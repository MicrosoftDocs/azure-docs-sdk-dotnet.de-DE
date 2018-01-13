<Type Name="ExitCodeRangeMapping" FullName="Microsoft.Azure.Batch.ExitCodeRangeMapping">
  <TypeSignature Language="C#" Value="public class ExitCodeRangeMapping" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitCodeRangeMapping extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitCodeRangeMapping" />
  <TypeSignature Language="F#" Value="type ExitCodeRangeMapping = class&#xA;    interface ITransportObjectProvider&lt;ExitCodeRangeMapping&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Eine Reihe von Exitcodes und wie der Batch-Dienst reagieren soll, wenn eine Aufgabe mit dem Exitcode innerhalb dieses Bereichs beendet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitCodeRangeMapping (int start, int end, Microsoft.Azure.Batch.ExitOptions exitOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 start, int32 end, class Microsoft.Azure.Batch.ExitOptions exitOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ExitCodeRangeMapping.#ctor(System.Int32,System.Int32,Microsoft.Azure.Batch.ExitOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ExitCodeRangeMapping : int * int * Microsoft.Azure.Batch.ExitOptions -&gt; Microsoft.Azure.Batch.ExitCodeRangeMapping" Usage="new Microsoft.Azure.Batch.ExitCodeRangeMapping (start, end, exitOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="System.Int32" />
        <Parameter Name="end" Type="System.Int32" />
        <Parameter Name="exitOptions" Type="Microsoft.Azure.Batch.ExitOptions" />
      </Parameters>
      <Docs>
        <param name="start">Die erste Exitcode im Bereich.</param>
        <param name="end">Der letzte Exitcode im Bereich.</param>
        <param name="exitOptions">Ein <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" /> angeben, wie der Batch-Dienst reagieren soll, wenn die Aufgabe beendet, mit dem Exitcode im Bereich wird <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" /> auf <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.End" /> inklusive.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public int End { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.End" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property End As Integer" />
      <MemberSignature Language="F#" Value="member this.End : int" Usage="Microsoft.Azure.Batch.ExitCodeRangeMapping.End" />
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
            Ruft die letzte Exitcode im Bereich ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Bereiche sind inklusiv. Z. B. wenn ein <see cref="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" /> gibt 8 "und" End 10 starten wird es Exitcodes, 8, 9 und 10 entspricht.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitOptions ExitOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitOptions ExitOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExitOptions As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.ExitOptions : Microsoft.Azure.Batch.ExitOptions" Usage="Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" /> angeben, wie der Batch-Dienst reagieren soll, wenn die Aufgabe beendet, mit dem Exitcode im Bereich wird <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" /> auf <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.End" /> inklusive.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public int Start { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Start As Integer" />
      <MemberSignature Language="F#" Value="member this.Start : int" Usage="Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" />
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
            Ruft den ersten Exitcode im Bereich ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Bereiche sind inklusiv. Z. B. wenn ein <see cref="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" /> gibt 8 "und" End 10 starten wird es Exitcodes, 8, 9 und 10 entspricht.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="SynchronousMethodExceptionBehavior" FullName="Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior">
  <TypeSignature Language="C#" Value="public class SynchronousMethodExceptionBehavior : Microsoft.Azure.Batch.BatchClientBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SynchronousMethodExceptionBehavior extends Microsoft.Azure.Batch.BatchClientBehavior" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior" />
  <TypeSignature Language="VB.NET" Value="Public Class SynchronousMethodExceptionBehavior&#xA;Inherits BatchClientBehavior" />
  <TypeSignature Language="F#" Value="type SynchronousMethodExceptionBehavior = class&#xA;    inherit BatchClientBehavior" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Batch.BatchClientBehavior</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ein <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> der gibt an, wie Ausnahmen von synchronen Methoden ausgelöst werden soll. 
            </summary>
    <remarks>
            Standardmäßig Ausnahmen synchrone Methoden die gleiche als asynchrone diejenigen.  Für die Kompatibilität mit Versionen des Clients Azure.Batch vor 4.0, geben Sie die <see cref="F:Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior.ThrowAggregateException" /> Verhalten von synchronen Methoden in ausgelöste Ausnahmen umschlossen werden ein <see cref="T:System.AggregateException" />.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="ThrowAggregateException">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior ThrowAggregateException;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior ThrowAggregateException" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior.ThrowAggregateException" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly ThrowAggregateException As SynchronousMethodExceptionBehavior " />
      <MemberSignature Language="F#" Value=" staticval mutable ThrowAggregateException : Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior" Usage="Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior.ThrowAggregateException" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Dieses Verhalten verursacht synchrone Methoden ausgelöst <see cref="T:System.AggregateException" /> bei einem Fehler.
            </summary>
        <remarks>
            Dies war der Standardwert <see cref="T:Microsoft.Azure.Batch.SynchronousMethodExceptionBehavior" /> von Azure.Batch-Versionen vor 4.0 verwendet werden.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>
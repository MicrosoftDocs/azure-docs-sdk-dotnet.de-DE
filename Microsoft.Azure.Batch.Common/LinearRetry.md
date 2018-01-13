<Type Name="LinearRetry" FullName="Microsoft.Azure.Batch.Common.LinearRetry">
  <TypeSignature Language="C#" Value="public class LinearRetry : Microsoft.Azure.Batch.Common.IRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LinearRetry extends System.Object implements class Microsoft.Azure.Batch.Common.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.LinearRetry" />
  <TypeSignature Language="VB.NET" Value="Public Class LinearRetry&#xA;Implements IRetryPolicy" />
  <TypeSignature Language="F#" Value="type LinearRetry = class&#xA;    interface IRetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Common.IRetryPolicy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt eine wiederholungsrichtlinie auf, die eine angegebene Anzahl an Wiederholungen unter Verwendung eines angegebenen festen Zeitintervalls zwischen den Wiederholungsversuchen ausführt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinearRetry (TimeSpan deltaBackoff, int maxRetries);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan deltaBackoff, int32 maxRetries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.LinearRetry.#ctor(System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deltaBackoff As TimeSpan, maxRetries As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Common.LinearRetry : TimeSpan * int -&gt; Microsoft.Azure.Batch.Common.LinearRetry" Usage="new Microsoft.Azure.Batch.Common.LinearRetry (deltaBackoff, maxRetries)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxRetries" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="deltaBackoff">Das backoffintervall zwischen Wiederholungsversuchen.</param>
        <param name="maxRetries">Die maximale Anzahl von Wiederholungsversuchen.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Common.LinearRetry" /> -Klasse mit dem angegebenen Delta und die maximale Anzahl von Wiederholungsversuchen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeltaBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan DeltaBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DeltaBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.LinearRetry.DeltaBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeltaBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DeltaBackoff : TimeSpan" Usage="Microsoft.Azure.Batch.Common.LinearRetry.DeltaBackoff" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das backoffintervall zwischen Wiederholungsversuchen an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumRetries">
      <MemberSignature Language="C#" Value="public int MaximumRetries { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaximumRetries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.LinearRetry.MaximumRetries" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumRetries As Integer" />
      <MemberSignature Language="F#" Value="member this.MaximumRetries : int" Usage="Microsoft.Azure.Batch.Common.LinearRetry.MaximumRetries" />
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
            Ruft die maximale Anzahl von Wiederholungsversuchen an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Common.RetryDecision&gt; ShouldRetryAsync (Exception exception, Microsoft.Azure.Batch.Common.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Common.RetryDecision&gt; ShouldRetryAsync(class System.Exception exception, class Microsoft.Azure.Batch.Common.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.LinearRetry.ShouldRetryAsync(System.Exception,Microsoft.Azure.Batch.Common.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetryAsync : Exception * Microsoft.Azure.Batch.Common.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Common.RetryDecision&gt;&#xA;override this.ShouldRetryAsync : Exception * Microsoft.Azure.Batch.Common.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Common.RetryDecision&gt;" Usage="linearRetry.ShouldRetryAsync (exception, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.Common.IRetryPolicy.ShouldRetryAsync(System.Exception,Microsoft.Azure.Batch.Common.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Common.RetryDecision&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Batch.Common.OperationContext" />
      </Parameters>
      <Docs>
        <param name="exception">Ein <see cref="T:System.Exception" /> -Objekt, das die letzte ermittelte Ausnahme darstellt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Batch.Common.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</param>
        <summary>
            Bestimmt, ob der Vorgang wiederholt werden und wie lange bis zum nächsten Versuch gewartet werden soll. 
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.Common.RetryDecision" /> Objekt, das angibt, ob ein erneuter Versuch ausgeführt werden soll.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
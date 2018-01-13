<Type Name="ExponentialRetry" FullName="Microsoft.Azure.Batch.Common.ExponentialRetry">
  <TypeSignature Language="C#" Value="public class ExponentialRetry : Microsoft.Azure.Batch.Common.IRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExponentialRetry extends System.Object implements class Microsoft.Azure.Batch.Common.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ExponentialRetry" />
  <TypeSignature Language="VB.NET" Value="Public Class ExponentialRetry&#xA;Implements IRetryPolicy" />
  <TypeSignature Language="F#" Value="type ExponentialRetry = class&#xA;    interface IRetryPolicy" />
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
            <span data-ttu-id="fc185-101">Stellt eine wiederholungsrichtlinie auf, die eine angegebene Anzahl an Wiederholungen unter Verwendung von ein Exponentielles Backoff-Schema bestimmt das Intervall zwischen Wiederholungsversuchen ausführt.</span><span class="sxs-lookup"><span data-stu-id="fc185-101">Represents a retry policy that performs a specified number of retries, using an exponential backoff scheme to determine the interval between retries.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExponentialRetry (TimeSpan deltaBackoff, int maxRetries);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan deltaBackoff, int32 maxRetries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.ExponentialRetry.#ctor(System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deltaBackoff As TimeSpan, maxRetries As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Common.ExponentialRetry : TimeSpan * int -&gt; Microsoft.Azure.Batch.Common.ExponentialRetry" Usage="new Microsoft.Azure.Batch.Common.ExponentialRetry (deltaBackoff, maxRetries)" />
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
        <param name="deltaBackoff"><span data-ttu-id="fc185-102">Das Backoff-Intervall zwischen zwei Wiederholungen einlegen, in dem die resultierende Wartezeit 2 beträgt ^ n \* DeltaBackoff (wobei n die Anzahl von Wiederholungen ist)</span><span class="sxs-lookup"><span data-stu-id="fc185-102">The backoff interval between retries, where the resulting backoff is 2^n \* deltaBackoff (where n is the number of retries)</span></span></param>
        <param name="maxRetries"><span data-ttu-id="fc185-103">Die maximale Anzahl von Wiederholungsversuchen.</span><span class="sxs-lookup"><span data-stu-id="fc185-103">The maximum number of retry attempts.</span></span></param>
        <summary>
            <span data-ttu-id="fc185-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Common.ExponentialRetry" /> -Klasse mit dem angegebenen Delta und die maximale Anzahl von Wiederholungsversuchen.</span><span class="sxs-lookup"><span data-stu-id="fc185-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.Common.ExponentialRetry" /> class using the specified delta and maximum number of retries.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeltaBackoff">
      <MemberSignature Language="C#" Value="public TimeSpan DeltaBackoff { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan DeltaBackoff" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.ExponentialRetry.DeltaBackoff" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeltaBackoff As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.DeltaBackoff : TimeSpan" Usage="Microsoft.Azure.Batch.Common.ExponentialRetry.DeltaBackoff" />
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
            <span data-ttu-id="fc185-105">Ruft das Backoff-Intervall zwischen zwei Wiederholungen einlegen, in dem die resultierende Wartezeit 2 beträgt ^ n \* DeltaBackoff (wobei n die Anzahl von Wiederholungen ist).</span><span class="sxs-lookup"><span data-stu-id="fc185-105">Gets the backoff interval between retries, where the resulting backoff is 2^n \* deltaBackoff (where n is the number of retries).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumRetries">
      <MemberSignature Language="C#" Value="public int MaximumRetries { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaximumRetries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.ExponentialRetry.MaximumRetries" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumRetries As Integer" />
      <MemberSignature Language="F#" Value="member this.MaximumRetries : int" Usage="Microsoft.Azure.Batch.Common.ExponentialRetry.MaximumRetries" />
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
            <span data-ttu-id="fc185-106">Ruft die maximale Anzahl von Wiederholungsversuchen an.</span><span class="sxs-lookup"><span data-stu-id="fc185-106">Gets the maximum number of retry attempts.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Common.RetryDecision&gt; ShouldRetryAsync (Exception exception, Microsoft.Azure.Batch.Common.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Common.RetryDecision&gt; ShouldRetryAsync(class System.Exception exception, class Microsoft.Azure.Batch.Common.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.ExponentialRetry.ShouldRetryAsync(System.Exception,Microsoft.Azure.Batch.Common.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetryAsync : Exception * Microsoft.Azure.Batch.Common.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Common.RetryDecision&gt;&#xA;override this.ShouldRetryAsync : Exception * Microsoft.Azure.Batch.Common.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Common.RetryDecision&gt;" Usage="exponentialRetry.ShouldRetryAsync (exception, operationContext)" />
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
        <param name="exception"><span data-ttu-id="fc185-107">Ein <see cref="T:System.Exception" /> -Objekt, das die letzte ermittelte Ausnahme darstellt.</span><span class="sxs-lookup"><span data-stu-id="fc185-107">An <see cref="T:System.Exception" /> object that represents the last exception encountered.</span></span></param>
        <param name="operationContext"><span data-ttu-id="fc185-108">Ein <see cref="T:Microsoft.Azure.Batch.Common.OperationContext" /> Objekt zum Nachverfolgen von des aktuellen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fc185-108">An <see cref="T:Microsoft.Azure.Batch.Common.OperationContext" /> object for tracking the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="fc185-109">Bestimmt, ob der Vorgang wiederholt werden und wie lange bis zum nächsten Versuch gewartet werden soll.</span><span class="sxs-lookup"><span data-stu-id="fc185-109">Determines if the operation should be retried and how long to wait until the next retry.</span></span> 
            </summary>
        <returns><span data-ttu-id="fc185-110">Ein <see cref="T:Microsoft.Azure.Batch.Common.RetryDecision" /> Objekt, das angibt, ob ein erneuter Versuch ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="fc185-110">A <see cref="T:Microsoft.Azure.Batch.Common.RetryDecision" /> object which specifies if a retry should be performed.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
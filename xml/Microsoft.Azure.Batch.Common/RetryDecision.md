<Type Name="RetryDecision" FullName="Microsoft.Azure.Batch.Common.RetryDecision">
  <TypeSignature Language="C#" Value="public sealed class RetryDecision" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RetryDecision extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.RetryDecision" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RetryDecision" />
  <TypeSignature Language="F#" Value="type RetryDecision = class" />
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
            <span data-ttu-id="7e7b8-101">Stellt eine Entscheidung getroffen ein <see cref="T:Microsoft.Azure.Batch.Common.IRetryPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="7e7b8-101">Represents a decision made by an <see cref="T:Microsoft.Azure.Batch.Common.IRetryPolicy" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NoRetry">
      <MemberSignature Language="C#" Value="public static readonly Microsoft.Azure.Batch.Common.RetryDecision NoRetry;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class Microsoft.Azure.Batch.Common.RetryDecision NoRetry" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.RetryDecision.NoRetry" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly NoRetry As RetryDecision " />
      <MemberSignature Language="F#" Value=" staticval mutable NoRetry : Microsoft.Azure.Batch.Common.RetryDecision" Usage="Microsoft.Azure.Batch.Common.RetryDecision.NoRetry" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.RetryDecision</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e7b8-102">Wiederholen Sie die Entscheidung mit <see cref="P:Microsoft.Azure.Batch.Common.RetryDecision.ShouldRetry" /> auf "false" festgelegt</span><span class="sxs-lookup"><span data-stu-id="7e7b8-102">A retry decision with <see cref="P:Microsoft.Azure.Batch.Common.RetryDecision.ShouldRetry" /> set to false</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryDelay">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetryDelay { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetryDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RetryDecision.RetryDelay" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetryDelay As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetryDelay : Nullable&lt;TimeSpan&gt;" Usage="Microsoft.Azure.Batch.Common.RetryDecision.RetryDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e7b8-103">Ruft die Verzögerung vor der nächsten Wiederholung ab.</span><span class="sxs-lookup"><span data-stu-id="7e7b8-103">Gets the delay before the next retry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryWithDelay">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Common.RetryDecision RetryWithDelay (TimeSpan retryDelay);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Common.RetryDecision RetryWithDelay(valuetype System.TimeSpan retryDelay) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Common.RetryDecision.RetryWithDelay(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RetryWithDelay (retryDelay As TimeSpan) As RetryDecision" />
      <MemberSignature Language="F#" Value="static member RetryWithDelay : TimeSpan -&gt; Microsoft.Azure.Batch.Common.RetryDecision" Usage="Microsoft.Azure.Batch.Common.RetryDecision.RetryWithDelay retryDelay" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.RetryDecision</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="retryDelay" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="retryDelay"><span data-ttu-id="7e7b8-104">Die Dauer, warten Sie vor dem Ausführen der versuchen Sie es erneut.</span><span class="sxs-lookup"><span data-stu-id="7e7b8-104">The duration to wait before performing the retry.</span></span></param>
        <summary>
            <span data-ttu-id="7e7b8-105">Erstellen Sie ein neues <see cref="T:Microsoft.Azure.Batch.Common.RetryDecision" /> mit der angegebenen Verzögerung vor der nächsten Wiederholung.</span><span class="sxs-lookup"><span data-stu-id="7e7b8-105">Create a new <see cref="T:Microsoft.Azure.Batch.Common.RetryDecision" /> with the specified delay before the next retry.</span></span>
            </summary>
        <returns><span data-ttu-id="7e7b8-106">Ein <see cref="T:Microsoft.Azure.Batch.Common.RetryDecision" /> Objekt mit dem angegebenen wiederholungsverzögerung und <see cref="P:Microsoft.Azure.Batch.Common.RetryDecision.ShouldRetry" /> auf "true" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="7e7b8-106">A <see cref="T:Microsoft.Azure.Batch.Common.RetryDecision" /> object with the specified retry delay and <see cref="P:Microsoft.Azure.Batch.Common.RetryDecision.ShouldRetry" /> set to true.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ShouldRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Common.RetryDecision.ShouldRetry" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ShouldRetry As Boolean" />
      <MemberSignature Language="F#" Value="member this.ShouldRetry : bool" Usage="Microsoft.Azure.Batch.Common.RetryDecision.ShouldRetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7e7b8-107">Ruft ab, ob ein erneuter Versuch ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="7e7b8-107">Gets whether a retry should be performed or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
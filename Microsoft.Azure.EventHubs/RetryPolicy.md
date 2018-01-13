<Type Name="RetryPolicy" FullName="Microsoft.Azure.EventHubs.RetryPolicy">
  <TypeSignature Language="C#" Value="public abstract class RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RetryPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.RetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c9635-101">Stellt eine Abstraktion für die Wiederholung Messagingvorgänge dar.</span><span class="sxs-lookup"><span data-stu-id="c9635-101">Represents an abstraction for retrying messaging operations.</span></span> <span data-ttu-id="c9635-102">Benutzer sollten diese Klasse nicht implementiert, und verwenden stattdessen eine der bereitgestellten Implementierungen.</span><span class="sxs-lookup"><span data-stu-id="c9635-102">Users should not implement this class, and instead should use one of the provided implementations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RetryPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.RetryPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.EventHubs.RetryPolicy Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.EventHubs.RetryPolicy Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.RetryPolicy.Clone" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Clone () As RetryPolicy" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.Azure.EventHubs.RetryPolicy" Usage="retryPolicy.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="c9635-103">Erstellt eine neue Kopie des aktuellen <see cref="T:Microsoft.Azure.EventHubs.RetryPolicy" /> und Klonen Sie es in eine neue Instanz.</span><span class="sxs-lookup"><span data-stu-id="c9635-103">Creates a new copy of the current <see cref="T:Microsoft.Azure.EventHubs.RetryPolicy" /> and clones it into a new instance.</span></span></summary>
        <returns><span data-ttu-id="c9635-104">Eine neue Kopie des <see cref="T:Microsoft.Azure.EventHubs.RetryPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="c9635-104">A new copy of <see cref="T:Microsoft.Azure.EventHubs.RetryPolicy" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.RetryPolicy Default { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.EventHubs.RetryPolicy Default" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.RetryPolicy.Default" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Default As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.Default : Microsoft.Azure.EventHubs.RetryPolicy" Usage="Microsoft.Azure.EventHubs.RetryPolicy.Default" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9635-105">Gibt die standardmäßige wiederholungsrichtlinie <see cref="T:Microsoft.Azure.EventHubs.RetryExponential" />.</span><span class="sxs-lookup"><span data-stu-id="c9635-105">Returns the default retry policy, <see cref="T:Microsoft.Azure.EventHubs.RetryExponential" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNextRetryInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; GetNextRetryInterval (string clientId, Exception lastException, TimeSpan remainingTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; GetNextRetryInterval(string clientId, class System.Exception lastException, valuetype System.TimeSpan remainingTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.RetryPolicy.GetNextRetryInterval(System.String,System.Exception,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNextRetryInterval (clientId As String, lastException As Exception, remainingTime As TimeSpan) As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.GetNextRetryInterval : string * Exception * TimeSpan -&gt; Nullable&lt;TimeSpan&gt;" Usage="retryPolicy.GetNextRetryInterval (clientId, lastException, remainingTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="lastException" Type="System.Exception" />
        <Parameter Name="remainingTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="c9635-106">Die <see cref="P:Microsoft.Azure.EventHubs.ClientEntity.ClientId" /> verknüpft sind, mit dem Vorgang zu wiederholen</span><span class="sxs-lookup"><span data-stu-id="c9635-106">The <see cref="P:Microsoft.Azure.EventHubs.ClientEntity.ClientId" /> associated with the operation to retry</span></span></param>
        <param name="lastException"><span data-ttu-id="c9635-107">Die letzte Ausnahme, die ausgelöst wurde</span><span class="sxs-lookup"><span data-stu-id="c9635-107">The last exception that was thrown</span></span></param>
        <param name="remainingTime"><span data-ttu-id="c9635-108">Verbleibende Zeit für das kumulative timeout</span><span class="sxs-lookup"><span data-stu-id="c9635-108">Remaining time for the cumulative timeout</span></span></param>
        <summary>
            <span data-ttu-id="c9635-109">Ruft die Zeitspanne für den nächsten wiederholen Sie den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="c9635-109">Gets the timespan for the next retry operation.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRetryCount">
      <MemberSignature Language="C#" Value="protected int GetRetryCount (string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance int32 GetRetryCount(string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.RetryPolicy.GetRetryCount(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Function GetRetryCount (clientId As String) As Integer" />
      <MemberSignature Language="F#" Value="member this.GetRetryCount : string -&gt; int" Usage="retryPolicy.GetRetryCount clientId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncrementRetryCount">
      <MemberSignature Language="C#" Value="public void IncrementRetryCount (string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void IncrementRetryCount(string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.RetryPolicy.IncrementRetryCount(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub IncrementRetryCount (clientId As String)" />
      <MemberSignature Language="F#" Value="member this.IncrementRetryCount : string -&gt; unit" Usage="retryPolicy.IncrementRetryCount clientId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="c9635-110">Die <see cref="P:Microsoft.Azure.EventHubs.ClientEntity.ClientId" /> verknüpft sind, mit dem Vorgang zu wiederholen</span><span class="sxs-lookup"><span data-stu-id="c9635-110">The <see cref="P:Microsoft.Azure.EventHubs.ClientEntity.ClientId" /> associated with the operation to retry</span></span></param>
        <summary>
            <span data-ttu-id="c9635-111">Erhöht die Anzahl der Wiederholungsversuche an.</span><span class="sxs-lookup"><span data-stu-id="c9635-111">Increases the retry count.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRetryableException">
      <MemberSignature Language="C#" Value="public static bool IsRetryableException (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsRetryableException(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.RetryPolicy.IsRetryableException(System.Exception)" />
      <MemberSignature Language="F#" Value="static member IsRetryableException : Exception -&gt; bool" Usage="Microsoft.Azure.EventHubs.RetryPolicy.IsRetryableException exception" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"></param>
        <summary>
            <span data-ttu-id="c9635-112">Legt fest, ob die Ausnahme, die wiederholt werden kann.</span><span class="sxs-lookup"><span data-stu-id="c9635-112">Determines whether or not the exception can be retried.</span></span>
            </summary>
        <returns><span data-ttu-id="c9635-113">Einen booleschen Wert, der angibt, ob der Vorgang wiederholt werden kann.</span><span class="sxs-lookup"><span data-stu-id="c9635-113">A bool indicating whether or not the operation can be retried.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NoRetry">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.EventHubs.RetryPolicy NoRetry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.Azure.EventHubs.RetryPolicy NoRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.EventHubs.RetryPolicy.NoRetry" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property NoRetry As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.NoRetry : Microsoft.Azure.EventHubs.RetryPolicy" Usage="Microsoft.Azure.EventHubs.RetryPolicy.NoRetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.EventHubs.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c9635-114">Gibt die standardmäßige wiederholungsrichtlinie <see cref="P:Microsoft.Azure.EventHubs.RetryPolicy.NoRetry" />.</span><span class="sxs-lookup"><span data-stu-id="c9635-114">Returns the default retry policy, <see cref="P:Microsoft.Azure.EventHubs.RetryPolicy.NoRetry" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnGetNextRetryInterval">
      <MemberSignature Language="C#" Value="protected abstract Nullable&lt;TimeSpan&gt; OnGetNextRetryInterval (string clientId, Exception lastException, TimeSpan remainingTime, int baseWaitTime);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; OnGetNextRetryInterval(string clientId, class System.Exception lastException, valuetype System.TimeSpan remainingTime, int32 baseWaitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.RetryPolicy.OnGetNextRetryInterval(System.String,System.Exception,System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnGetNextRetryInterval (clientId As String, lastException As Exception, remainingTime As TimeSpan, baseWaitTime As Integer) As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="abstract member OnGetNextRetryInterval : string * Exception * TimeSpan * int -&gt; Nullable&lt;TimeSpan&gt;" Usage="retryPolicy.OnGetNextRetryInterval (clientId, lastException, remainingTime, baseWaitTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="lastException" Type="System.Exception" />
        <Parameter Name="remainingTime" Type="System.TimeSpan" />
        <Parameter Name="baseWaitTime" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="clientId"></param>
        <param name="lastException"></param>
        <param name="remainingTime"></param>
        <param name="baseWaitTime"></param>
        <summary />
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetRetryCount">
      <MemberSignature Language="C#" Value="public void ResetRetryCount (string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void ResetRetryCount(string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.RetryPolicy.ResetRetryCount(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResetRetryCount (clientId As String)" />
      <MemberSignature Language="F#" Value="member this.ResetRetryCount : string -&gt; unit" Usage="retryPolicy.ResetRetryCount clientId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs</AssemblyName>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="c9635-115">Die <see cref="P:Microsoft.Azure.EventHubs.ClientEntity.ClientId" /> verknüpft sind, mit dem Vorgang zu wiederholen</span><span class="sxs-lookup"><span data-stu-id="c9635-115">The <see cref="P:Microsoft.Azure.EventHubs.ClientEntity.ClientId" /> associated with the operation to retry</span></span></param>
        <summary>
            <span data-ttu-id="c9635-116">Setzt die Anzahl der Wiederholungsversuche auf 0 (null) zurück.</span><span class="sxs-lookup"><span data-stu-id="c9635-116">Resets the retry count to zero.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
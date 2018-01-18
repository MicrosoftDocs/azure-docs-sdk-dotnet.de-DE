<Type Name="RetryPolicy" FullName="Microsoft.ServiceBus.RetryPolicy">
  <TypeSignature Language="C#" Value="public abstract class RetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RetryPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.RetryPolicy" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RetryPolicy" />
  <TypeSignature Language="F#" Value="type RetryPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cd689-101">Stellt eine Abstraktion für die Wiederholung Messagingvorgänge dar.</span><span class="sxs-lookup"><span data-stu-id="cd689-101">Represents an abstraction for retrying messaging operations.</span></span> <span data-ttu-id="cd689-102">Benutzer sollten diese Klasse nicht implementiert, und verwenden stattdessen eine der bereitgestellten Implementierungen.</span><span class="sxs-lookup"><span data-stu-id="cd689-102">Users should not implement this class, and instead should use one of the provided implementations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public abstract Microsoft.ServiceBus.RetryPolicy Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceBus.RetryPolicy Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.Clone" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function Clone () As RetryPolicy" />
      <MemberSignature Language="F#" Value="abstract member Clone : unit -&gt; Microsoft.ServiceBus.RetryPolicy" Usage="retryPolicy.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary><span data-ttu-id="cd689-103">Erstellt eine neue Kopie des aktuellen <see cref="T:Microsoft.ServiceBus.RetryPolicy" /> und Klonen Sie es in eine neue Instanz.</span><span class="sxs-lookup"><span data-stu-id="cd689-103">Creates a new copy of the current <see cref="T:Microsoft.ServiceBus.RetryPolicy" /> and clones it into a new instance.</span></span></summary>
        <returns><span data-ttu-id="cd689-104">Eine neue Kopie des <see cref="T:Microsoft.ServiceBus.RetryPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="cd689-104">A new copy of <see cref="T:Microsoft.ServiceBus.RetryPolicy" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Default">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.RetryPolicy Default { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ServiceBus.RetryPolicy Default" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryPolicy.Default" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Default As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.Default : Microsoft.ServiceBus.RetryPolicy" Usage="Microsoft.ServiceBus.RetryPolicy.Default" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cd689-105">Ruft eine Instanz von der <see cref="T:Microsoft.ServiceBus.RetryExponential" /> wiederholungsrichtlinie auf, die eine Standardinstallation von exponentiell erhöhen Wiederholungsintervalle für Messagingvorgänge bereitstellt.</span><span class="sxs-lookup"><span data-stu-id="cd689-105">Gets an instance of the  <see cref="T:Microsoft.ServiceBus.RetryExponential" /> retry policy, which provides a default setup of exponentially increasing retry intervals for messaging operations.</span></span> <span data-ttu-id="cd689-106">Jedes Mal, wenn diese Eigenschaft zugegriffen wird, wird eine neue Instanz erstellt.</span><span class="sxs-lookup"><span data-stu-id="cd689-106">Each time this property is accessed, a new instance is created.</span></span>
            </summary>
        <value><span data-ttu-id="cd689-107">Die Standardrichtlinie, die der Richtlinie zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="cd689-107">The default policy associated with the policy.</span></span></value>
        <remarks><span data-ttu-id="cd689-108">Diese Eigenschaft ist die folgende Instanz dadurch auf effektive Weise.</span><span class="sxs-lookup"><span data-stu-id="cd689-108">This property is effectively creating the following instance.</span></span>
            <code>
               var policy = new RetryExponential(
                                    TimeSpan.Zero,
                                    TimeSpan.FromSeconds(30),
                                    10);                 
            </code>
            
            <span data-ttu-id="cd689-109">Es ist wichtig zu beachten, dass die wiederholungsrichtlinie immer berücksichtigt werden sollten die <seealso cref="P:Microsoft.ServiceBus.Messaging.ClientEntity.OperationTimeout" /> damit, wiederholen Sie den Vorgang beendet wird, wenn es sich bei der nächsten Wiederholungsintervall wird das die Vorgang Zeit überschreitet.</span><span class="sxs-lookup"><span data-stu-id="cd689-109">It is important to note that the retry policy should always honor the <seealso cref="P:Microsoft.ServiceBus.Messaging.ClientEntity.OperationTimeout" /> so that retry will terminate if the next retry interval will exceed the operation time.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsRetryableException">
      <MemberSignature Language="C#" Value="protected abstract bool IsRetryableException (Exception lastException);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool IsRetryableException(class System.Exception lastException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.IsRetryableException(System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function IsRetryableException (lastException As Exception) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member IsRetryableException : Exception -&gt; bool" Usage="retryPolicy.IsRetryableException lastException" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lastException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="lastException"><span data-ttu-id="cd689-110">Die neuesten aufgetretene Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="cd689-110">The latest occurred exception.</span></span></param>
        <summary><span data-ttu-id="cd689-111">Bestimmt, ob es nach der angegebenen Ausnahme erfolgen zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="cd689-111">Determines whether it is permissible to retry after the specified exception.</span></span></summary>
        <returns><span data-ttu-id="cd689-112">Wenn diese Methode "false" zurückgibt, tritt keine Wiederholung.</span><span class="sxs-lookup"><span data-stu-id="cd689-112">If this method returns false, no retry occurs.</span></span> <span data-ttu-id="cd689-113">Andernfalls die <see cref="M:Microsoft.ServiceBus.RetryPolicy.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" /> Methode bestimmt, wann zu wiederholen.</span><span class="sxs-lookup"><span data-stu-id="cd689-113">Otherwise, the <see cref="M:Microsoft.ServiceBus.RetryPolicy.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" /> method determines when to retry.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NoRetry">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.RetryPolicy NoRetry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ServiceBus.RetryPolicy NoRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.RetryPolicy.NoRetry" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property NoRetry As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.NoRetry : Microsoft.ServiceBus.RetryPolicy" Usage="Microsoft.ServiceBus.RetryPolicy.NoRetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cd689-114">Ruft eine Instanz von der <see cref="P:Microsoft.ServiceBus.RetryPolicy.NoRetry" /> wiederholungsrichtlinie auf, wodurch effektiv Wiederholungen deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="cd689-114">Gets an instance of the <see cref="P:Microsoft.ServiceBus.RetryPolicy.NoRetry" /> retry policy, which effectively disables retries.</span></span>
            <span data-ttu-id="cd689-115">Bei jedem wird Zugriff auf diese Eigenschaft eine neue Instanz zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="cd689-115">Each time this property is accessed, a new instance is returned.</span></span>
            </summary>
        <value><span data-ttu-id="cd689-116">Eine wiederholungsrichtlinie, die keine Wiederholungen ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="cd689-116">A retry policy that performs no retries.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnShouldRetry">
      <MemberSignature Language="C#" Value="protected abstract bool OnShouldRetry (TimeSpan remainingTime, int currentRetryCount, out TimeSpan retryInterval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance bool OnShouldRetry(valuetype System.TimeSpan remainingTime, int32 currentRetryCount, [out] valuetype System.TimeSpan&amp; retryInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.OnShouldRetry(System.TimeSpan,System.Int32,System.TimeSpan@)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function OnShouldRetry (remainingTime As TimeSpan, currentRetryCount As Integer, ByRef retryInterval As TimeSpan) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member OnShouldRetry : TimeSpan * int *  -&gt; bool" Usage="retryPolicy.OnShouldRetry (remainingTime, currentRetryCount, retryInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="remainingTime" Type="System.TimeSpan" />
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="remainingTime"><span data-ttu-id="cd689-117">Die verbleibende Zeit.</span><span class="sxs-lookup"><span data-stu-id="cd689-117">The remaining time.</span></span></param>
        <param name="currentRetryCount"><span data-ttu-id="cd689-118">Die Gesamtanzahl der Wiederholungen.</span><span class="sxs-lookup"><span data-stu-id="cd689-118">The total number of retries.</span></span></param>
        <param name="retryInterval"><span data-ttu-id="cd689-119">Das Wiederholungsintervall.</span><span class="sxs-lookup"><span data-stu-id="cd689-119">The retry interval.</span></span></param>
        <summary><span data-ttu-id="cd689-120">Berechnet das Wiederholungsintervall für die wiederholungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="cd689-120">Calculates the retry interval for the retry policy.</span></span></summary>
        <returns><span data-ttu-id="cd689-121">Wenn diese Methode gibt "true" zurück, der Wiederholungsvorgang auftritt, nachdem der Thread für eine bestimmte Zeitspanne gleich in den Leerlauf wechselt <paramref name="retryInterval" />.</span><span class="sxs-lookup"><span data-stu-id="cd689-121">If this method returns true, the retry operation occurs after the thread becomes idle for an amount of time equal to <paramref name="retryInterval" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetServerBusyInternal">
      <MemberSignature Language="C#" Value="protected virtual void ResetServerBusyInternal ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void ResetServerBusyInternal() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.ResetServerBusyInternal" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub ResetServerBusyInternal ()" />
      <MemberSignature Language="F#" Value="abstract member ResetServerBusyInternal : unit -&gt; unit&#xA;override this.ResetServerBusyInternal : unit -&gt; unit" Usage="retryPolicy.ResetServerBusyInternal " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServerBusy">
      <MemberSignature Language="C#" Value="protected void SetServerBusy (string exceptionMessage);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void SetServerBusy(string exceptionMessage) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.SetServerBusy(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub SetServerBusy (exceptionMessage As String)" />
      <MemberSignature Language="F#" Value="member this.SetServerBusy : string -&gt; unit" Usage="retryPolicy.SetServerBusy exceptionMessage" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exceptionMessage" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="exceptionMessage"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServerBusyInternal">
      <MemberSignature Language="C#" Value="protected virtual void SetServerBusyInternal ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void SetServerBusyInternal() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.RetryPolicy.SetServerBusyInternal" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub SetServerBusyInternal ()" />
      <MemberSignature Language="F#" Value="abstract member SetServerBusyInternal : unit -&gt; unit&#xA;override this.SetServerBusyInternal : unit -&gt; unit" Usage="retryPolicy.SetServerBusyInternal " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
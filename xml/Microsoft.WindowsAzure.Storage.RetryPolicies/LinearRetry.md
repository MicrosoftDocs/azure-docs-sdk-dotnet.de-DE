<Type Name="LinearRetry" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry">
  <TypeSignature Language="C#" Value="public sealed class LinearRetry : Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LinearRetry extends System.Object implements class Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LinearRetry&#xA;Implements IExtendedRetryPolicy" />
  <TypeSignature Language="F#" Value="type LinearRetry = class&#xA;    interface IExtendedRetryPolicy&#xA;    interface IRetryPolicy" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="73181-101">Stellt eine wiederholungsrichtlinie auf, die eine angegebene Anzahl an Wiederholungen unter Verwendung eines angegebenen festen Zeitintervalls zwischen den Wiederholungsversuchen ausführt.</span><span class="sxs-lookup"><span data-stu-id="73181-101">Represents a retry policy that performs a specified number of retries, using a specified fixed time interval between retries.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinearRetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="73181-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="73181-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinearRetry (TimeSpan deltaBackoff, int maxAttempts);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan deltaBackoff, int32 maxAttempts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.#ctor(System.TimeSpan,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (deltaBackoff As TimeSpan, maxAttempts As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry : TimeSpan * int -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" Usage="new Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry (deltaBackoff, maxAttempts)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="deltaBackoff" Type="System.TimeSpan" />
        <Parameter Name="maxAttempts" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="deltaBackoff"><span data-ttu-id="73181-103">Ein <see cref="T:System.TimeSpan" /> das Backoff-Intervall zwischen den Wiederholungen angeben.</span><span class="sxs-lookup"><span data-stu-id="73181-103">A <see cref="T:System.TimeSpan" /> specifying the back-off interval between retries.</span></span></param>
        <param name="maxAttempts"><span data-ttu-id="73181-104">Eine ganze Zahl, die die maximale Anzahl der Wiederholungsversuche angibt.</span><span class="sxs-lookup"><span data-stu-id="73181-104">An integer specifying the maximum number of retry attempts.</span></span></param>
        <summary>
            <span data-ttu-id="73181-105">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" /> -Klasse mit dem angegebenen Delta und die maximale Anzahl von Wiederholungsversuchen.</span><span class="sxs-lookup"><span data-stu-id="73181-105">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry" /> class using the specified delta and maximum number of retries.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateInstance">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy CreateInstance() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.CreateInstance" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateInstance () As IRetryPolicy" />
      <MemberSignature Language="F#" Value="abstract member CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy&#xA;override this.CreateInstance : unit -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" Usage="linearRetry.CreateInstance " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy.CreateInstance</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="73181-106">Generiert eine neue wiederholungsrichtlinie für den aktuellen Anforderungsversuch.</span><span class="sxs-lookup"><span data-stu-id="73181-106">Generates a new retry policy for the current request attempt.</span></span>
            </summary>
        <returns><span data-ttu-id="73181-107">Ein <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" /> Objekt, das die wiederholungsrichtlinie für den aktuellen Anforderungsversuch darstellt.</span><span class="sxs-lookup"><span data-stu-id="73181-107">An <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" /> object that represents the retry policy for the current request attempt.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Evaluate">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo Evaluate (Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo Evaluate(class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.Evaluate(Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Evaluate : Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo&#xA;override this.Evaluate : Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" Usage="linearRetry.Evaluate (retryContext, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.RetryPolicies.IExtendedRetryPolicy.Evaluate(Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="retryContext" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="retryContext"><span data-ttu-id="73181-108">Ein <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" /> -Objekt, das die weist darauf hin wiederholt, die Ergebnisse der letzten Anforderung und, ob der nächste Versuch sollte in der primären oder sekundären Speicherort erfolgen, und gibt den Positionsmodus an.</span><span class="sxs-lookup"><span data-stu-id="73181-108">A <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" /> object that indicates the number of retries, the results of the last request, and whether the next retry should happen in the primary or secondary location, and specifies the location mode.</span></span></param>
        <param name="operationContext"><span data-ttu-id="73181-109">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="73181-109">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="73181-110">Bestimmt, ob der Vorgang wiederholt werden sollte und das Intervall bis zur nächsten Wiederholung.</span><span class="sxs-lookup"><span data-stu-id="73181-110">Determines whether the operation should be retried and the interval until the next retry.</span></span>
            </summary>
        <returns><span data-ttu-id="73181-111">Ein <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> -Objekt, das den Positionsmodus gibt an, und gibt an, ob der nächste Versuch am primären oder sekundären Speicherort geschehen soll.</span><span class="sxs-lookup"><span data-stu-id="73181-111">A <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> object that indicates the location mode, and whether the next retry should happen in the primary or secondary location.</span></span> <span data-ttu-id="73181-112">Wenn <c>null</c>, der Vorgang wird nicht wiederholt werden.</span><span class="sxs-lookup"><span data-stu-id="73181-112">If <c>null</c>, the operation will not be retried.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry (int currentRetryCount, int statusCode, Exception lastException, out TimeSpan retryInterval, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool ShouldRetry(int32 currentRetryCount, int32 statusCode, class System.Exception lastException, [out] valuetype System.TimeSpan&amp; retryInterval, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.LinearRetry.ShouldRetry(System.Int32,System.Int32,System.Exception,System.TimeSpan@,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool&#xA;override this.ShouldRetry : int * int * Exception *  * Microsoft.WindowsAzure.Storage.OperationContext -&gt; bool" Usage="linearRetry.ShouldRetry (currentRetryCount, statusCode, lastException, retryInterval, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy.ShouldRetry(System.Int32,System.Int32,System.Exception,System.TimeSpan@,Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentRetryCount" Type="System.Int32" />
        <Parameter Name="statusCode" Type="System.Int32" />
        <Parameter Name="lastException" Type="System.Exception" />
        <Parameter Name="retryInterval" Type="System.TimeSpan&amp;" RefType="out" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="currentRetryCount"><span data-ttu-id="73181-113">Eine ganze Zahl, die die Anzahl der Wiederholungsversuche für den angegebenen Vorgang angeben.</span><span class="sxs-lookup"><span data-stu-id="73181-113">An integer specifying the number of retries for the given operation.</span></span> <span data-ttu-id="73181-114">Wert 0 (null) gibt an, dass dies der erste Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="73181-114">A value of zero signifies this is the first error encountered.</span></span></param>
        <param name="statusCode"><span data-ttu-id="73181-115">Eine ganze Zahl, die den Statuscode für den letzten Vorgang enthält.</span><span class="sxs-lookup"><span data-stu-id="73181-115">An integer containing the status code for the last operation.</span></span></param>
        <param name="lastException"><span data-ttu-id="73181-116">Ein <see cref="T:System.Exception" /> -Objekt, das die letzte ermittelte Ausnahme darstellt.</span><span class="sxs-lookup"><span data-stu-id="73181-116">An <see cref="T:System.Exception" /> object that represents the last exception encountered.</span></span></param>
        <param name="retryInterval"><span data-ttu-id="73181-117">Ein <see cref="T:System.TimeSpan" /> , der angibt, des Wartezeitintervall bis zur nächsten Wiederholung.</span><span class="sxs-lookup"><span data-stu-id="73181-117">A <see cref="T:System.TimeSpan" /> indicating the interval to wait until the next retry.</span></span></param>
        <param name="operationContext"><span data-ttu-id="73181-118">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="73181-118">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="73181-119">Bestimmt, ob der Vorgang wiederholt werden sollte und das Intervall bis zur nächsten Wiederholung.</span><span class="sxs-lookup"><span data-stu-id="73181-119">Determines whether the operation should be retried and the interval until the next retry.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="73181-120"><c>"true"</c> , wenn der Vorgang wiederholt; andernfalls werden soll <c>"false"</c>.</span><span class="sxs-lookup"><span data-stu-id="73181-120"><c>true</c> if the operation should be retried; otherwise, <c>false</c>.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
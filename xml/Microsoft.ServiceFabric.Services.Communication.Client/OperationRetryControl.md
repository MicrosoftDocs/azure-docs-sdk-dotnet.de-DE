<Type Name="OperationRetryControl" FullName="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl">
  <TypeSignature Language="C#" Value="public class OperationRetryControl" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OperationRetryControl extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl" />
  <TypeSignature Language="VB.NET" Value="Public Class OperationRetryControl" />
  <TypeSignature Language="F#" Value="type OperationRetryControl = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="72fc3-101">Gibt an, dass die wiederholungsrichtlinie für die Ausnahmen bei der Kommunikation vom Client zum Dienst erhalten.</span><span class="sxs-lookup"><span data-stu-id="72fc3-101">Specifies the retry policy for the exceptions got on the communication from client to service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OperationRetryControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.Exception" />
      <MemberSignature Language="VB.NET" Value="Public Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72fc3-102">Diese Ausnahme Bericht für den Vorgang, wenn ShouldRetry auf "false" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="72fc3-102">Exception to report for the operation, if ShouldRetry is false.</span></span> <span data-ttu-id="72fc3-103">Standardmäßig ist dies die gleiche Ausnahme wie die gemeldeten Ausnahme jedoch in einigen Fällen die Factory Trasform gemeldete Ausnahme in eine aussagekräftigere Ausnahme nach Wunsch kann.</span><span class="sxs-lookup"><span data-stu-id="72fc3-103">By default this is the same exception as the reported exception, however in some cases the Factory may choose to trasform the reported exception to a more meaningful exception.</span></span>
            </summary>
        <value><span data-ttu-id="72fc3-104">Ausnahme</span><span class="sxs-lookup"><span data-stu-id="72fc3-104">Exception</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExceptionId">
      <MemberSignature Language="C#" Value="public string ExceptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExceptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ExceptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ExceptionId As String" />
      <MemberSignature Language="F#" Value="member this.ExceptionId : string with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ExceptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72fc3-105">Eine Zeichenfolge, die eindeutig den Typ der Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="72fc3-105">String that uniquely identifies the exception type.</span></span>
            </summary>
        <value><span data-ttu-id="72fc3-106">Eindeutige Id für diese Ausnahme ausgelöst.</span><span class="sxs-lookup"><span data-stu-id="72fc3-106">Unique id for this exception.</span></span> <span data-ttu-id="72fc3-107">Diese Id wird verwendet, um zu verfolgen die Anzahl der Male, die diese Ausnahme wird wiederholt</span><span class="sxs-lookup"><span data-stu-id="72fc3-107">This id is used to keep track of the number of times this exception is retried</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.IsTransient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72fc3-108">Wenn die ShouldRetry-Eigenschaft auf "true" festgelegt ist, gibt diese Eigenschaft an, ob es sich bei der Kommunikationskanal zwischen dem Client und Dienst noch gültig ist.</span><span class="sxs-lookup"><span data-stu-id="72fc3-108">If the ShouldRetry property is true, this property indicates if the communication channel between the client and service is still valid.</span></span>
            <span data-ttu-id="72fc3-109">Vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen die Kommunikationskanals vom Client zum Dienst noch vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="72fc3-109">Transient retriable exceptions are those where the communication channel from client to service still exists.</span></span>
            <span data-ttu-id="72fc3-110">Nicht vorübergehende Ausnahmen, die wiederholbar sind diejenigen, in denen wir müssen den Dienstendpunkt erneut zu beheben, bevor es versucht.</span><span class="sxs-lookup"><span data-stu-id="72fc3-110">Non transient retriable exceptions are those where we need to re-resolve the service endpoint before we retry.</span></span>
            </summary>
        <value>
            <span data-ttu-id="72fc3-111">"true" gibt an, dass dies eine vorübergehende wiederholbar Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="72fc3-111">true indicates that this is a transient retriable exception.</span></span>
            <span data-ttu-id="72fc3-112">False gibt an, dass dies ein nicht vorübergehender wiederholbar Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="72fc3-112">false indicates that this is a non transient retriable exception.</span></span>
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxRetryCount">
      <MemberSignature Language="C#" Value="public int MaxRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.MaxRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxRetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxRetryCount : int with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.MaxRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72fc3-113">Maximale Anzahl der Häufigkeit, mit die diesem Vorgang wiederholt werden sollte, wenn die ShouldRetry auf "true" festgelegt ist</span><span class="sxs-lookup"><span data-stu-id="72fc3-113">Max number of times this operation should be retried if the ShouldRetry is true</span></span>
            </summary>
        <value><span data-ttu-id="72fc3-114">Max-Wiederholungsanzahl</span><span class="sxs-lookup"><span data-stu-id="72fc3-114">Max retry count</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryDelay">
      <MemberSignature Language="C#" Value="public TimeSpan RetryDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RetryDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.RetryDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RetryDelay : TimeSpan with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.RetryDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72fc3-115">Der Vorgang sollte nach dieser Verzögerung erneut versucht werden, wenn die ShouldRetry auf "true" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="72fc3-115">The operation should be retried after this delay if the ShouldRetry is true.</span></span>
            </summary>
        <value><span data-ttu-id="72fc3-116">Die Verzögerung, die nach dem der Vorgang wiederholt werden sollte</span><span class="sxs-lookup"><span data-stu-id="72fc3-116">Time delay after which the operation should be retried</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShouldRetry">
      <MemberSignature Language="C#" Value="public bool ShouldRetry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ShouldRetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ShouldRetry" />
      <MemberSignature Language="VB.NET" Value="Public Property ShouldRetry As Boolean" />
      <MemberSignature Language="F#" Value="member this.ShouldRetry : bool with get, set" Usage="Microsoft.ServiceFabric.Services.Communication.Client.OperationRetryControl.ShouldRetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72fc3-117">Gibt an, ob der Vorgang wiederholt werden soll.</span><span class="sxs-lookup"><span data-stu-id="72fc3-117">Indicates whether the operation should be retried or not.</span></span>
            </summary>
        <value><span data-ttu-id="72fc3-118">"true", wenn der Vorgang muss wiederholt werden – "false", wenn die Ausnahme an den Benutzer ausgelöst werden soll</span><span class="sxs-lookup"><span data-stu-id="72fc3-118">true if the operation should be retried, false if the exception should be thrown to the user</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
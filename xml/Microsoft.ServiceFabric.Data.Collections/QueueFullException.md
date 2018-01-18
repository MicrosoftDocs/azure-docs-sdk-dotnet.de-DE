<Type Name="QueueFullException" FullName="Microsoft.ServiceFabric.Data.Collections.QueueFullException">
  <TypeSignature Language="C#" Value="public class QueueFullException : System.Fabric.FabricTransientException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit QueueFullException extends System.Fabric.FabricTransientException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" />
  <TypeSignature Language="VB.NET" Value="Public Class QueueFullException&#xA;Inherits FabricTransientException" />
  <TypeSignature Language="F#" Value="type QueueFullException = class&#xA;    inherit FabricTransientException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricTransientException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="51ea6-101">Ausgelöst von <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> Wenn die Warteschlangenkapazität erreicht wurde.</span><span class="sxs-lookup"><span data-stu-id="51ea6-101">Thrown by <see cref="M:Microsoft.ServiceFabric.Data.Collections.IReliableConcurrentQueue`1.EnqueueAsync(Microsoft.ServiceFabric.Data.ITransaction,`0,System.Threading.CancellationToken,System.Nullable{System.TimeSpan})" /> when the queue capacity has been reached.</span></span>
            </summary>
    <remarks>
      <para>
            <span data-ttu-id="51ea6-102">Wiederholbar; wird festgestellt, dass diese Ausnahme ausgelöst, sollte der Aufrufer einige Zeit in die Warteschlange einzureihen zusätzliche Vorgänge vor dem Ausstellen von einer anderen Warteschlange warten.</span><span class="sxs-lookup"><span data-stu-id="51ea6-102">Retriable; when encountering this exception, the caller should wait some time for additional enqueue operations before issuing another dequeue.</span></span>
            </para>
      <para>
            <span data-ttu-id="51ea6-103">Warteschlangenkapazität ist derzeit nicht implementiert.</span><span class="sxs-lookup"><span data-stu-id="51ea6-103">Queue capacity is not currently implemented.</span></span>
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueFullException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.QueueFullException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="51ea6-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="51ea6-104">Initializes a new Instance of the <see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueFullException (string msg);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string msg) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.QueueFullException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (msg As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Collections.QueueFullException : string -&gt; Microsoft.ServiceFabric.Data.Collections.QueueFullException" Usage="new Microsoft.ServiceFabric.Data.Collections.QueueFullException msg" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="msg" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="msg"><span data-ttu-id="51ea6-105">Die Meldung, in der der Fehler beschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="51ea6-105">The message that describes the error.</span></span></param>
        <summary>
            <span data-ttu-id="51ea6-106">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" /> Klasse mit einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="51ea6-106">Initializes a new Instance of the <see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QueueFullException (string msg, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string msg, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.Collections.QueueFullException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (msg As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.Collections.QueueFullException : string * Exception -&gt; Microsoft.ServiceFabric.Data.Collections.QueueFullException" Usage="new Microsoft.ServiceFabric.Data.Collections.QueueFullException (msg, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="msg" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="msg"><span data-ttu-id="51ea6-107">Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="51ea6-107">The error message that explains the reason for the exception.</span></span></param>
        <param name="innerException"><span data-ttu-id="51ea6-108">Die Ausnahme, die die Ursache für die aktuelle Ausnahme oder ein null-Verweis ist, wenn keine innere Ausnahme angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="51ea6-108">The exception that is the cause of the current exception, or a null reference if no inner exception is specified.</span></span></param>
        <summary>
            <span data-ttu-id="51ea6-109">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" />-Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="51ea6-109">Initializes a new instance of the <see cref="T:Microsoft.ServiceFabric.Data.Collections.QueueFullException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
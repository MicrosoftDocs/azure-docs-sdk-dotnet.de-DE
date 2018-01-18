<Type Name="RelayException" FullName="Microsoft.Azure.Relay.RelayException">
  <TypeSignature Language="C#" Value="public class RelayException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit RelayException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.RelayException" />
  <TypeSignature Language="VB.NET" Value="Public Class RelayException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type RelayException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="54715-101">Stellt für Relay Fehler ausgelösten Ausnahmen dar.</span><span class="sxs-lookup"><span data-stu-id="54715-101">Represents exceptions thrown for for relay errors.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="54715-102">Erstellt eine neue Instanz der <see cref="T:Microsoft.Azure.Relay.RelayException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="54715-102">Creates a new instance of the <see cref="T:Microsoft.Azure.Relay.RelayException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.RelayException : string -&gt; Microsoft.Azure.Relay.RelayException" Usage="new Microsoft.Azure.Relay.RelayException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="54715-103">Die Meldung, in der der Fehler beschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="54715-103">The message that describes the error.</span></span></param>
        <summary>
            <span data-ttu-id="54715-104">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.Azure.Relay.RelayException" /> Klasse mit einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="54715-104">Creates a new instance of the <see cref="T:Microsoft.Azure.Relay.RelayException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RelayException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.RelayException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Relay.RelayException" Usage="new Microsoft.Azure.Relay.RelayException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info"><span data-ttu-id="54715-105">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" />, die die serialisierten Objektdaten für die ausgelöste Ausnahme enthält.</span><span class="sxs-lookup"><span data-stu-id="54715-105">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> that holds the serialized object data about the exception being thrown.</span></span> </param>
        <param name="context"><span data-ttu-id="54715-106">Der <see cref="T:System.Runtime.Serialization.StreamingContext" />, der die Kontextinformationen über die Quelle oder das Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="54715-106">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> that contains contextual information about the source or destination.</span></span> </param>
        <summary>
            <span data-ttu-id="54715-107">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.Azure.Relay.RelayException" /> -Klasse mit serialisierten Daten.</span><span class="sxs-lookup"><span data-stu-id="54715-107">Creates a new instance of the <see cref="T:Microsoft.Azure.Relay.RelayException" /> class with serialized data.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RelayException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.RelayException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.RelayException : string * Exception -&gt; Microsoft.Azure.Relay.RelayException" Usage="new Microsoft.Azure.Relay.RelayException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="54715-108">Die Meldung, in der der Fehler beschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="54715-108">The message that describes the error.</span></span></param>
        <param name="innerException"><span data-ttu-id="54715-109">Die Ausnahme, die die Ursache der aktuellen Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="54715-109">The exception that is the cause of the current exception.</span></span></param>
        <summary>
            <span data-ttu-id="54715-110">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.Azure.Relay.RelayException" /> Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="54715-110">Creates a new instance of the <see cref="T:Microsoft.Azure.Relay.RelayException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTransient">
      <MemberSignature Language="C#" Value="public bool IsTransient { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsTransient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Relay.RelayException.IsTransient" />
      <MemberSignature Language="VB.NET" Value="Public Property IsTransient As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsTransient : bool with get, set" Usage="Microsoft.Azure.Relay.RelayException.IsTransient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="54715-111">Ruft einen Wert, der angibt, ob die Ausnahme flüchtig ist.</span><span class="sxs-lookup"><span data-stu-id="54715-111">Gets a value indicating whether the exception is transient.</span></span> <span data-ttu-id="54715-112">Überprüfen Sie diese Eigenschaft, um zu bestimmen, ob der Vorgang wiederholt werden sollte.</span><span class="sxs-lookup"><span data-stu-id="54715-112">Check this property to determine if the operation should be retried.</span></span></summary>
        <value><span data-ttu-id="54715-113">"true", wenn die Ausnahme vorübergehenden; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="54715-113">true if the exception is transient; otherwise, false.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
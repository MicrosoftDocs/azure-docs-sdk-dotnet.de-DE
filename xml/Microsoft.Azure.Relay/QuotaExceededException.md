<Type Name="QuotaExceededException" FullName="Microsoft.Azure.Relay.QuotaExceededException">
  <TypeSignature Language="C#" Value="public class QuotaExceededException : Microsoft.Azure.Relay.RelayException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit QuotaExceededException extends Microsoft.Azure.Relay.RelayException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.QuotaExceededException" />
  <TypeSignature Language="VB.NET" Value="Public Class QuotaExceededException&#xA;Inherits RelayException" />
  <TypeSignature Language="F#" Value="type QuotaExceededException = class&#xA;    inherit RelayException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Relay.RelayException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="11d9a-101">Eine Ausnahme, die angibt, ein Relay-Kontingent wurde überschritten.</span><span class="sxs-lookup"><span data-stu-id="11d9a-101">An exception indicating a Relay quota has been exceeded.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QuotaExceededException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.QuotaExceededException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="11d9a-102">Erstellt eine neue Instanz der <see cref="T:Microsoft.Azure.Relay.QuotaExceededException" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="11d9a-102">Creates a new instance of the <see cref="T:Microsoft.Azure.Relay.QuotaExceededException" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QuotaExceededException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.QuotaExceededException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.QuotaExceededException : string -&gt; Microsoft.Azure.Relay.QuotaExceededException" Usage="new Microsoft.Azure.Relay.QuotaExceededException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="11d9a-103">Die Meldung, in der der Fehler beschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="11d9a-103">The message that describes the error.</span></span></param>
        <summary>
            <span data-ttu-id="11d9a-104">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.Azure.Relay.QuotaExceededException" /> Klasse mit einer angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="11d9a-104">Creates a new instance of the <see cref="T:Microsoft.Azure.Relay.QuotaExceededException" /> class with a specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected QuotaExceededException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.QuotaExceededException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.QuotaExceededException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Relay.QuotaExceededException" Usage="new Microsoft.Azure.Relay.QuotaExceededException (info, context)" />
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
        <param name="info"><span data-ttu-id="11d9a-105">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" />, die die serialisierten Objektdaten für die ausgelöste Ausnahme enthält.</span><span class="sxs-lookup"><span data-stu-id="11d9a-105">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> that holds the serialized object data about the exception being thrown.</span></span> </param>
        <param name="context"><span data-ttu-id="11d9a-106">Der <see cref="T:System.Runtime.Serialization.StreamingContext" />, der die Kontextinformationen über die Quelle oder das Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="11d9a-106">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> that contains contextual information about the source or destination.</span></span> </param>
        <summary>
            <span data-ttu-id="11d9a-107">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.Azure.Relay.QuotaExceededException" /> -Klasse mit serialisierten Daten.</span><span class="sxs-lookup"><span data-stu-id="11d9a-107">Creates a new instance of the <see cref="T:Microsoft.Azure.Relay.QuotaExceededException" /> class with serialized data.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public QuotaExceededException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.QuotaExceededException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.QuotaExceededException : string * Exception -&gt; Microsoft.Azure.Relay.QuotaExceededException" Usage="new Microsoft.Azure.Relay.QuotaExceededException (message, innerException)" />
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
        <param name="message"><span data-ttu-id="11d9a-108">Die Meldung, in der der Fehler beschrieben wird.</span><span class="sxs-lookup"><span data-stu-id="11d9a-108">The message that describes the error.</span></span></param>
        <param name="innerException"><span data-ttu-id="11d9a-109">Die Ausnahme, die die Ursache der aktuellen Ausnahme ist.</span><span class="sxs-lookup"><span data-stu-id="11d9a-109">The exception that is the cause of the current exception.</span></span></param>
        <summary>
            <span data-ttu-id="11d9a-110">Erstellt eine neue Instanz der dem <see cref="T:Microsoft.Azure.Relay.QuotaExceededException" /> Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="11d9a-110">Creates a new instance of the <see cref="T:Microsoft.Azure.Relay.QuotaExceededException" /> class with a specified error message and a reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
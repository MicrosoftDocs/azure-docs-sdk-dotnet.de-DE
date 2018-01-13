<Type Name="MultiShardSchemaMismatchException" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException">
  <TypeSignature Language="C#" Value="public class MultiShardSchemaMismatchException : Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit MultiShardSchemaMismatchException extends Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiShardSchemaMismatchException&#xA;Inherits MultiShardException" />
  <TypeSignature Language="F#" Value="type MultiShardSchemaMismatchException = class&#xA;    inherit MultiShardException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Naming", "CA1704:IdentifiersShouldBeSpelledCorrectly", MessageId="Multi")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="7c182-101">Benutzerdefinierte Ausnahme wird ausgelöst, wenn das Schema für mindestens eine der Einbeziehung in die gesamte Abfrage Shards nicht das erwartete Schema für die Abfrage mit mehreren Shard als Ganzes entspricht.</span><span class="sxs-lookup"><span data-stu-id="7c182-101">Custom exception thrown when the schema on at least one of the shards participating in the overall query does not conform to the expected schema for the multi-shard query as a whole.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardSchemaMismatchException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7c182-102">Initialisiert eine neue Instanz der MultiShardSchemaMismatchException-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7c182-102">Initializes a new instance of the MultiShardSchemaMismatchException class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardSchemaMismatchException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException : string -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"> <span data-ttu-id="7c182-103">auszuführenden Debuggerabbilds die Meldung, die die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="7c182-103">specifices the message that explains the reason for the exception.</span></span></param>
        <summary>
            <span data-ttu-id="7c182-104">Initialisiert eine neue Instanz der Klasse MultiShardSchemaMismatchException mit der angegebenen Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="7c182-104">Initializes a new instance of the MultiShardSchemaMismatchException class with the specified error message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MultiShardSchemaMismatchException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
            <span data-ttu-id="7c182-105">Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> finden, die die serialisierten Objektdaten zur ausgelösten Ausnahme enthält.</span><span class="sxs-lookup"><span data-stu-id="7c182-105">The <see cref="T:System.Runtime.Serialization.SerializationInfo" /> see that holds the serialized object data about the exception being thrown.</span></span>
            </param>
        <param name="context">
            <span data-ttu-id="7c182-106">Der <see cref="T:System.Runtime.Serialization.StreamingContext" />, der die Kontextinformationen über die Quelle oder das Ziel enthält.</span><span class="sxs-lookup"><span data-stu-id="7c182-106">The <see cref="T:System.Runtime.Serialization.StreamingContext" /> that contains contextual information about the source or destination.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c182-107">Initialisiert eine neue Instanz der MultiShardSchemaMismatchException-Klasse mit serialisierten Daten.</span><span class="sxs-lookup"><span data-stu-id="7c182-107">Initializes a new instance of the MultiShardSchemaMismatchException class with serialized data.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiShardSchemaMismatchException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException : string * Exception -&gt; Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException" Usage="new Microsoft.Azure.SqlDatabase.ElasticScale.Query.MultiShardSchemaMismatchException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message"> <span data-ttu-id="7c182-108">auszuführenden Debuggerabbilds die Meldung, die die Ursache der Ausnahme erklärt wird.</span><span class="sxs-lookup"><span data-stu-id="7c182-108">specifices the message that explains the reason for the exception.</span></span></param>
        <param name="innerException"> <span data-ttu-id="7c182-109">Gibt an, die an den Shard aufgetretene Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="7c182-109">specifies the exception encountered at the shard.</span></span></param>
        <summary>
            <span data-ttu-id="7c182-110">Initialisiert eine neue Instanz der Klasse MultiShardSchemaMismatchException mit der angegebenen Fehlermeldung und der Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.</span><span class="sxs-lookup"><span data-stu-id="7c182-110">Initializes a new instance of the MultiShardSchemaMismatchException class with the specified error message and the reference to the inner exception that is the cause of this exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
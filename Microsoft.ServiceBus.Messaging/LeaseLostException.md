<Type Name="LeaseLostException" FullName="Microsoft.ServiceBus.Messaging.LeaseLostException">
  <TypeSignature Language="C#" Value="public class LeaseLostException : Exception" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit LeaseLostException extends System.Exception" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.LeaseLostException" />
  <TypeSignature Language="VB.NET" Value="Public Class LeaseLostException&#xA;Inherits Exception" />
  <TypeSignature Language="F#" Value="type LeaseLostException = class&#xA;    inherit Exception" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Exception</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Repräsentiert eine Ausnahme, die auftritt, wenn die Dienst Lease unterbrochen wurde.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LeaseLostException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" />-Klasse mit Standardwerten.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LeaseLostException (Microsoft.ServiceBus.Messaging.Lease lease);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.Messaging.Lease lease) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.#ctor(Microsoft.ServiceBus.Messaging.Lease)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.LeaseLostException : Microsoft.ServiceBus.Messaging.Lease -&gt; Microsoft.ServiceBus.Messaging.LeaseLostException" Usage="new Microsoft.ServiceBus.Messaging.LeaseLostException lease" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
      </Parameters>
      <Docs>
        <param name="lease">Die messaging-Lease.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" /> -Klasse unter Verwendung der angegebenen Lease.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LeaseLostException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.LeaseLostException : string -&gt; Microsoft.ServiceBus.Messaging.LeaseLostException" Usage="new Microsoft.ServiceBus.Messaging.LeaseLostException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die Meldung des Fehlers.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" /> -Klasse unter Verwendung der angegebenen Fehlermeldung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LeaseLostException (Microsoft.ServiceBus.Messaging.Lease lease, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceBus.Messaging.Lease lease, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.#ctor(Microsoft.ServiceBus.Messaging.Lease,System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.LeaseLostException : Microsoft.ServiceBus.Messaging.Lease * Exception -&gt; Microsoft.ServiceBus.Messaging.LeaseLostException" Usage="new Microsoft.ServiceBus.Messaging.LeaseLostException (lease, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.ServiceBus.Messaging.Lease" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="lease">Die messaging-Lease.</param>
        <param name="innerException">Der Fehler, der die Ausnahme verursacht hat.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" /> -Klasse mit der angegebenen Lease und der Fehler, der die Ausnahme verursacht hat.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected LeaseLostException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.LeaseLostException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.ServiceBus.Messaging.LeaseLostException" Usage="new Microsoft.ServiceBus.Messaging.LeaseLostException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">Die serialisierten Informationen zur Ausnahme.</param>
        <param name="context">Die Kontextinformationen zur Quelle bzw. zum Ziel.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" /> -Klasse mit angegebenen Informationen und dem angegebenen Kontext.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LeaseLostException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.LeaseLostException : string * Exception -&gt; Microsoft.ServiceBus.Messaging.LeaseLostException" Usage="new Microsoft.ServiceBus.Messaging.LeaseLostException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">Die Meldung des Fehlers.</param>
        <param name="innerException">Der Fehler, der die Ausnahme verursacht hat.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.LeaseLostException" /> Klasse unter Verwendung von angegebenen Fehlermeldung und inneren Ausnahme.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetObjectData">
      <MemberSignature Language="C#" Value="public override void GetObjectData (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void GetObjectData(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.LeaseLostException.GetObjectData(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub GetObjectData (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="override this.GetObjectData : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; unit" Usage="leaseLostException.GetObjectData (info, context)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">Das mit Daten aufzufüllende <see cref="T:System.Runtime.Serialization.SerializationInfo" />-Objekt.</param>
        <param name="context">Das Ziel (Siehe StreamingContext) dieser Serialisierung.</param>
        <summary>Füllt eine <see cref="T:System.Runtime.Serialization.SerializationInfo" /> mit den Daten auf, die zum Serialisieren des Zielobjekts erforderlich sind.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Lease">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.Lease Lease { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ServiceBus.Messaging.Lease Lease" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.LeaseLostException.Lease" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Lease As Lease" />
      <MemberSignature Language="F#" Value="member this.Lease : Microsoft.ServiceBus.Messaging.Lease" Usage="Microsoft.ServiceBus.Messaging.LeaseLostException.Lease" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.Lease</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ermittelt oder definiert die Dienst-Lease.</summary>
        <value>Die Dienst-Lease.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
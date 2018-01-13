<Type Name="FabricBackupInProgressException" FullName="System.Fabric.FabricBackupInProgressException">
  <TypeSignature Language="C#" Value="public class FabricBackupInProgressException : System.Fabric.FabricException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit FabricBackupInProgressException extends System.Fabric.FabricException" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricBackupInProgressException" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricBackupInProgressException&#xA;Inherits FabricException" />
  <TypeSignature Language="F#" Value="type FabricBackupInProgressException = class&#xA;    inherit FabricException" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.FabricException</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.MaintainabilityRules", "SA1402:FileMayOnlyContainASingleClass", Justification="Exception")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para>Die Ausnahme, die ausgelöst wird, bei dem Versuch, eine Sicherung zu initiieren, während eine zuvor begonnene Sicherung noch ausgeführt wird.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricBackupInProgressException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricBackupInProgressException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricBackupInProgressException" /> Klasse mit dem Fehlercode <see cref="F:System.Fabric.FabricErrorCode.BackupInProgress" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricBackupInProgressException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricBackupInProgressException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricBackupInProgressException : string -&gt; System.Fabric.FabricBackupInProgressException" Usage="new System.Fabric.FabricBackupInProgressException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der Klasse mit dem Fehlercode FabricBackupInProgressException <see cref="F:System.Fabric.FabricErrorCode.BackupInProgress" /> und einer angegebenen Fehlermeldung.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected FabricBackupInProgressException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricBackupInProgressException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricBackupInProgressException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; System.Fabric.FabricBackupInProgressException" Usage="new System.Fabric.FabricBackupInProgressException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">
          <para>Die <see cref="T:System.Runtime.Serialization.SerializationInfo" /> -Objekt mit serialisierten Objektdaten für die ausgelöste Ausnahme.</para>
        </param>
        <param name="context">
          <para>Das <see cref="T:System.Runtime.Serialization.StreamingContext" />-Objekt, das die Kontextinformationen für die Quelle oder das Ziel enthält. Der Kontextparameter ist für die zukünftige Verwendung reserviert und kann null sein.</para>
        </param>
        <summary>
          <para>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricBackupInProgressException" /> Klasse aus einem serialisierten Objekt, mit einem angegebenen Kontext.
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricBackupInProgressException (string message, Exception inner);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception inner) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricBackupInProgressException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, inner As Exception)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricBackupInProgressException : string * Exception -&gt; System.Fabric.FabricBackupInProgressException" Usage="new System.Fabric.FabricBackupInProgressException (message, inner)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="inner" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">
          <para>Die Fehlermeldung, in der die Ursache der Ausnahme erklärt wird.</para>
        </param>
        <param name="inner">
          <para>Die Ausnahme, die die Ursache der aktuellen Ausnahme oder Null ist, wenn keine innere Ausnahme angegeben wird. Die <see cref="T:System.Exception" /> Klasse erhalten Sie weitere Informationen zur inneren Ausnahme.</para>
        </param>
        <summary>
          <para>
            Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricBackupInProgressException" />-Klasse mit einer angegebenen Fehlermeldung und einem Verweis auf die innere Ausnahme, die diese Ausnahme ausgelöst hat.
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
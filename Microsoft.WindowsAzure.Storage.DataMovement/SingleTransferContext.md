<Type Name="SingleTransferContext" FullName="Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext">
  <TypeSignature Language="C#" Value="public class SingleTransferContext : Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SingleTransferContext extends Microsoft.WindowsAzure.Storage.DataMovement.TransferContext" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />
  <TypeSignature Language="VB.NET" Value="Public Class SingleTransferContext&#xA;Inherits TransferContext" />
  <TypeSignature Language="F#" Value="type SingleTransferContext = class&#xA;    inherit TransferContext" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.DataMovement.TransferContext</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt den Kontext für eine einzelnes Übertragung dar und bietet zusätzliche Laufzeitinformationen zu dessen Ausführung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SingleTransferContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SingleTransferContext (Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint checkpoint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint checkpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext.#ctor(Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (checkpoint As TransferCheckpoint)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext : Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint -&gt; Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext checkpoint" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="checkpoint" Type="Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" />
      </Parameters>
      <Docs>
        <param name="checkpoint">Ein <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferCheckpoint" /> Objekt, das den letzten Prüfpunkt aus der die Übertragung fortgesetzt wird darstellt.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SingleTransferContext (System.IO.Stream journalStream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream journalStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext.#ctor(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (journalStream As Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" Usage="new Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext journalStream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="journalStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="journalStream">Der Stream, in dem die Übertragung Journal Infos in geschrieben wird. Sie können die Previours fortsetzen Übertragung von seinen Stream Journal angehalten.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.SingleTransferContext" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="TransferConfigurations" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations">
  <TypeSignature Language="C#" Value="public class TransferConfigurations" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferConfigurations extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferConfigurations" />
  <TypeSignature Language="F#" Value="type TransferConfigurations = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            TransferConfigurations-Klasse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferConfigurations ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.#ctor" />
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlockSize">
      <MemberSignature Language="C#" Value="public int BlockSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BlockSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.BlockSize" />
      <MemberSignature Language="VB.NET" Value="Public Property BlockSize As Integer" />
      <MemberSignature Language="F#" Value="member this.BlockSize : int with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.BlockSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Blockgröße zum Windows Azure-Speicher übertragen zu gehörte blockiert. Es muss zwischen 4MB und 100MB und werden mehrere 4 MB.
            
            Derzeit ist die Anzahl der max-Block eines Block-BLOBs auf 50000 beschränkt.
            Beim Übertragen einer großen Datei und die Blockgröße bereitgestellt ist kleiner als der Mindestwert - (Größe/50000), es muss zurückgesetzt werden auf einen Wert größer als der Minimalwert und mehrere 4 MB für diese Datei.
            </summary>
        <value>BlockSize zum Windows Azure-Speicher übertragen zu können.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParallelOperations">
      <MemberSignature Language="C#" Value="public int ParallelOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ParallelOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.ParallelOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property ParallelOperations As Integer" />
      <MemberSignature Language="F#" Value="member this.ParallelOperations : int with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.ParallelOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Elemente aus ein Wert, der angibt, wie viele arbeiten, die gleichzeitig verarbeiten. Herunterladen oder Hochladen von ein einzelnes Blob kann eine große Anzahl von Arbeitsaufgaben bestehen.
            </summary>
        <value>Wie viele Arbeitsaufgaben gleichzeitig verarbeiten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAgentPrefix">
      <MemberSignature Language="C#" Value="public string UserAgentPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserAgentPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.UserAgentPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAgentPrefix As String" />
      <MemberSignature Language="F#" Value="member this.UserAgentPrefix : string with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.UserAgentPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Benutzer-Agent-Präfix
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
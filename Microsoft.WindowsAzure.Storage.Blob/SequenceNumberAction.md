<Type Name="SequenceNumberAction" FullName="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction">
  <TypeSignature Language="C#" Value="public enum SequenceNumberAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SequenceNumberAction extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction" />
  <TypeSignature Language="VB.NET" Value="Public Enum SequenceNumberAction" />
  <TypeSignature Language="F#" Value="type SequenceNumberAction = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Beschreibt Aktionen, die für die Sequenznummer eines Blob ausgeführt werden können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Increment">
      <MemberSignature Language="C#" Value="Increment" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction Increment = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction.Increment" />
      <MemberSignature Language="VB.NET" Value="Increment" />
      <MemberSignature Language="F#" Value="Increment = 2" Usage="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction.Increment" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Erhöht den Wert der Sequenznummer um 1.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Max">
      <MemberSignature Language="C#" Value="Max" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction Max = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction.Max" />
      <MemberSignature Language="VB.NET" Value="Max" />
      <MemberSignature Language="F#" Value="Max = 0" Usage="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction.Max" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Legt die Sequenznummer auf den höheren der in der Anforderung enthaltenen Werte und den derzeit für das Blob gespeicherten Wert fest.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="Update" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction Update = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction.Update" />
      <MemberSignature Language="VB.NET" Value="Update" />
      <MemberSignature Language="F#" Value="Update = 1" Usage="Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction.Update" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.SequenceNumberAction</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Legt die Sequenznummer auf den in der Anforderung enthaltenen Wert fest.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>
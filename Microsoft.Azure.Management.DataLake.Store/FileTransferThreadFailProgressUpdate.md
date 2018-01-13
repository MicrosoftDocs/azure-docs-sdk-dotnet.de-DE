<Type Name="FileTransferThreadFailProgressUpdate" FullName="Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate">
  <TypeSignature Language="C#" Value="public delegate void FileTransferThreadFailProgressUpdate(TransferMetadata failedFile);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed FileTransferThreadFailProgressUpdate extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.FileTransferThreadFailProgressUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Sub FileTransferThreadFailProgressUpdate(failedFile As TransferMetadata)" />
  <TypeSignature Language="F#" Value="type FileTransferThreadFailProgressUpdate = delegate of TransferMetadata -&gt; unit" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="failedFile" Type="Microsoft.Azure.Management.DataLake.Store.TransferMetadata" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Void</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="failedFile">To be added.</param>
    <summary>
            Stellt einen Delegaten, der im Falle einer Übertragung Thread aufgerufen wird, eine Datei unerwartet beendet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>
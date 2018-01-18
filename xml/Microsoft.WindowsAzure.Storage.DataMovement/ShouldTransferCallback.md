<Type Name="ShouldTransferCallback" FullName="Microsoft.WindowsAzure.Storage.DataMovement.ShouldTransferCallback">
  <TypeSignature Language="C#" Value="public delegate bool ShouldTransferCallback(object source, object destination);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ShouldTransferCallback extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.ShouldTransferCallback" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function ShouldTransferCallback(source As Object, destination As Object) As Boolean " />
  <TypeSignature Language="F#" Value="type ShouldTransferCallback = delegate of obj * obj -&gt; bool" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="source" Type="System.Object" />
    <Parameter Name="destination" Type="System.Object" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Boolean</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="source"><span data-ttu-id="f3952-101">Die Instanz von der Übertragungsquelle.</span><span class="sxs-lookup"><span data-stu-id="f3952-101">Instance of the transfer source.</span></span></param>
    <param name="destination"><span data-ttu-id="f3952-102">Die Instanz des Ziels für die Übertragung.</span><span class="sxs-lookup"><span data-stu-id="f3952-102">Instance of the transfer destination.</span></span></param>
    <summary>
            <span data-ttu-id="f3952-103">Der Rückruf aufgerufen wird, um festzustellen, ob eine Übertragung erfolgen soll.</span><span class="sxs-lookup"><span data-stu-id="f3952-103">Callback invoked to tell whether a transfer should be done.</span></span>
            </summary>
    <returns><span data-ttu-id="f3952-104">True, wenn die Übertragung erfolgen soll. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="f3952-104">True if the transfer should be done; otherwise false.</span></span></returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>
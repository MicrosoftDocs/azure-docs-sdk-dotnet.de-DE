<Type Name="SetAttributesCallback" FullName="Microsoft.WindowsAzure.Storage.DataMovement.SetAttributesCallback">
  <TypeSignature Language="C#" Value="public delegate void SetAttributesCallback(object destination);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SetAttributesCallback extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.SetAttributesCallback" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Sub SetAttributesCallback(destination As Object)" />
  <TypeSignature Language="F#" Value="type SetAttributesCallback = delegate of obj -&gt; unit" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="destination" Type="System.Object" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Void</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="destination"><span data-ttu-id="b3426-101">Die Instanz des Ziels, das überschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="b3426-101">Instance of destination to be overwritten.</span></span></param>
    <summary>
            <span data-ttu-id="b3426-102">Der Rückruf aufgerufen wird, um die Attribute des Ziels im Arbeitsspeicher festgelegt.</span><span class="sxs-lookup"><span data-stu-id="b3426-102">Callback invoked to set destination's attributes in memory.</span></span> <span data-ttu-id="b3426-103">Der Attributsatz in dieser Rückruf werden an Azure Storage-Dienst gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="b3426-103">The attributes set in this callback will be sent to azure storage service.</span></span> 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>
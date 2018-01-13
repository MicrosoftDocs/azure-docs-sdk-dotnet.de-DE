<Type Name="FabricClient+ClaimsRetrievalEventHandler" FullName="System.Fabric.FabricClient+ClaimsRetrievalEventHandler">
  <TypeSignature Language="C#" Value="public delegate string FabricClient.ClaimsRetrievalEventHandler(object sender, FabricClient.ClaimsRetrievalEventArgs e);" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed FabricClient/ClaimsRetrievalEventHandler extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ClaimsRetrievalEventHandler" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Function FabricClient.ClaimsRetrievalEventHandler(sender As Object, e As FabricClient.ClaimsRetrievalEventArgs) As String " />
  <TypeSignature Language="F#" Value="type FabricClient.ClaimsRetrievalEventHandler = delegate of obj * FabricClient.ClaimsRetrievalEventArgs -&gt; string" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="sender" Type="System.Object" />
    <Parameter Name="e" Type="System.Fabric.FabricClient+ClaimsRetrievalEventArgs" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.String</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="sender">
      <para>Ein Verweis auf die <see cref="T:System.Fabric.FabricClient" /> Instanz, in dem das Ereignis ausgelöst wird.</para>
    </param>
    <param name="e">
      <para>Die Ereignisargumente.</para>
      <seealso cref="T:System.Fabric.FabricClient.ClaimsRetrievalEventArgs" />
    </param>
    <summary>
            Delegat für die Behandlung von Ansprüchen token abrufen Rückruf durch Registrieren für das ClaimsRetrieval-Ereignis
            </summary>
    <returns>To be added.</returns>
    <remarks>To be added.</remarks>
  </Docs>
</Type>
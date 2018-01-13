<Type Name="ConnectionStatusChangesHandler" FullName="Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler">
  <TypeSignature Language="C#" Value="public delegate void ConnectionStatusChangesHandler(ConnectionStatus status, ConnectionStatusChangeReason reason);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectionStatusChangesHandler extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.Client.ConnectionStatusChangesHandler" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Sub ConnectionStatusChangesHandler(status As ConnectionStatus, reason As ConnectionStatusChangeReason)" />
  <TypeSignature Language="F#" Value="type ConnectionStatusChangesHandler = delegate of ConnectionStatus * ConnectionStatusChangeReason -&gt; unit" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices.Client</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="status" Type="Microsoft.Azure.Devices.Client.ConnectionStatus" />
    <Parameter Name="reason" Type="Microsoft.Azure.Devices.Client.ConnectionStatusChangeReason" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Void</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="status"><span data-ttu-id="2a18d-101">Der Status wurde aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="2a18d-101">The updated connection status</span></span></param>
    <param name="reason"><span data-ttu-id="2a18d-102">Der Grund für die Änderung des Verbindungsstatus</span><span class="sxs-lookup"><span data-stu-id="2a18d-102">The reason for the connection status change</span></span></param>
    <summary>
            <span data-ttu-id="2a18d-103">Der Delegat für den Verbindungsstatus geändert.</span><span class="sxs-lookup"><span data-stu-id="2a18d-103">Delegate for connection status changed.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>
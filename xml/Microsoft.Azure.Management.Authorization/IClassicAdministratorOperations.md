<Type Name="IClassicAdministratorOperations" FullName="Microsoft.Azure.Management.Authorization.IClassicAdministratorOperations">
  <TypeSignature Language="C#" Value="public interface IClassicAdministratorOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IClassicAdministratorOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.IClassicAdministratorOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IClassicAdministratorOperations" />
  <TypeSignature Language="F#" Value="type IClassicAdministratorOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8302a-101">Rufen Sie Details des klassischen Administrators (http://TBD für Weitere Informationen siehe)</span><span class="sxs-lookup"><span data-stu-id="8302a-101">Get classic administrator details  (see http://TBD for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.ClassicAdministratorListResult&gt; ListAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.ClassicAdministratorListResult&gt; ListAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IClassicAdministratorOperations.ListAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.ClassicAdministratorListResult&gt;" Usage="iClassicAdministratorOperations.ListAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.ClassicAdministratorListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
            <span data-ttu-id="8302a-102">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8302a-102">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8302a-103">Ruft eine Liste der klassischen Administratoren für das Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="8302a-103">Gets a list of classic administrators for the subscription.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8302a-104">Ergebnis Listeninformationen ClassicAdministrator.</span><span class="sxs-lookup"><span data-stu-id="8302a-104">ClassicAdministrator list result information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
<Type Name="ApplicationTypePagedList" FullName="System.Fabric.Query.ApplicationTypePagedList">
  <TypeSignature Language="C#" Value="public sealed class ApplicationTypePagedList : System.Fabric.Query.PagedList&lt;System.Fabric.Query.ApplicationType&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationTypePagedList extends System.Fabric.Query.PagedList`1&lt;class System.Fabric.Query.ApplicationType&gt;" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ApplicationTypePagedList" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationTypePagedList&#xA;Inherits PagedList(Of ApplicationType)" />
  <TypeSignature Language="F#" Value="type ApplicationTypePagedList = class&#xA;    inherit PagedList&lt;ApplicationType&gt;" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.PagedList&lt;System.Fabric.Query.ApplicationType&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">System.Fabric.Query.ApplicationType</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="1f501-101">Stellt eine Seite <see cref="T:System.Fabric.Query.ApplicationType" /> abgerufen, die durch den Aufruf <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span><span class="sxs-lookup"><span data-stu-id="1f501-101">Represents one page of <see cref="T:System.Fabric.Query.ApplicationType" /> retrieved by calling <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />.</span></span> <span data-ttu-id="1f501-102">Ausgelagerte Listen bestehen aus den zurückgegebenen Ergebnisse es enthält (eine Liste), zusammen mit der ein Fortsetzungstoken, die zum Zugriff auf den nachfolgender Seiten verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="1f501-102">Paged lists consist of the return results it holds (a list), along with a continuation token which may be used to access subsequent pages.</span></span></para>
    </summary>
    <remarks>
      <para>
                    <span data-ttu-id="1f501-103">Wenn eine nachfolgende Seite vorhanden ist, kann das Fortsetzungstoken bereitgestellt, die in diesem Objekt verwendet werden, für den Zugriff darauf.</span><span class="sxs-lookup"><span data-stu-id="1f501-103">If there is a subsequent page, the continuation token provided in this object can be used to access it.</span></span>
                    <span data-ttu-id="1f501-104">Fortsetzung tokenverwendung Anweisungen hierzu finden Sie unter <see cref="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ContinuationToken" />.</span><span class="sxs-lookup"><span data-stu-id="1f501-104">For continuation token usage instructions, see <see cref="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ContinuationToken" />.</span></span>
                </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationTypePagedList ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.ApplicationTypePagedList.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="1f501-105">Erstellt ein leeres ausgelagerten <see cref="T:System.Fabric.Query.ApplicationType" /> Liste.</span><span class="sxs-lookup"><span data-stu-id="1f501-105">Creates an empty paged <see cref="T:System.Fabric.Query.ApplicationType" /> list.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
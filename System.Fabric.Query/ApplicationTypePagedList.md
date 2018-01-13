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
      <para>Stellt eine Seite <see cref="T:System.Fabric.Query.ApplicationType" /> abgerufen, die durch den Aufruf <see cref="M:System.Fabric.FabricClient.QueryClient.GetApplicationTypePagedListAsync" />. Ausgelagerte Listen bestehen aus den zurückgegebenen Ergebnisse es enthält (eine Liste), zusammen mit der ein Fortsetzungstoken, die zum Zugriff auf den nachfolgender Seiten verwendet werden kann.</para>
    </summary>
    <remarks>
      <para>
                    Wenn eine nachfolgende Seite vorhanden ist, kann das Fortsetzungstoken bereitgestellt, die in diesem Objekt verwendet werden, für den Zugriff darauf.
                    Fortsetzung tokenverwendung Anweisungen hierzu finden Sie unter <see cref="P:System.Fabric.Description.PagedApplicationTypeQueryDescription.ContinuationToken" />.
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
            Erstellt ein leeres ausgelagerten <see cref="T:System.Fabric.Query.ApplicationType" /> Liste.
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>
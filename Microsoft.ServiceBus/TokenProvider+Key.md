<Type Name="TokenProvider+Key" FullName="Microsoft.ServiceBus.TokenProvider+Key">
  <TypeSignature Language="C#" Value="protected internal class TokenProvider.Key : IEquatable&lt;Microsoft.ServiceBus.TokenProvider.Key&gt;" />
  <TypeSignature Language="ILAsm" Value=".class nested protected auto ansi beforefieldinit TokenProvider/Key extends System.Object implements class System.IEquatable`1&lt;class Microsoft.ServiceBus.TokenProvider/Key&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.TokenProvider.Key" />
  <TypeSignature Language="VB.NET" Value="Protected Friend Class TokenProvider.Key&#xA;Implements IEquatable(Of TokenProvider.Key)" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.ServiceBus.TokenProvider+Key&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Key (string appliesTo, string claim);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string appliesTo, string claim) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Key.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (appliesTo As String, claim As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.TokenProvider.Key : string * string -&gt; Microsoft.ServiceBus.TokenProvider.Key" Usage="new Microsoft.ServiceBus.TokenProvider.Key (appliesTo, claim)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="claim" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="appliesTo">Gibt die Adresse, wobei der Schlüssel für gilt.</param>
        <param name="claim">Gibt an, einen bestimmten Benutzer, Anwendung, Computer oder andere Entität</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.TokenProvider.Key" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.ServiceBus.TokenProvider.Key other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.ServiceBus.TokenProvider/Key other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Key.Equals(Microsoft.ServiceBus.TokenProvider.Key)" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As TokenProvider.Key) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.ServiceBus.TokenProvider.Key -&gt; bool" Usage="key.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.ServiceBus.TokenProvider+Key" />
      </Parameters>
      <Docs>
        <param name="other">Der Schlüssel, mit dem aktuellen Objekt verglichen werden soll.</param>
        <summary>Bestimmt, ob der angegebene Schlüssel mit dem aktuellen Objekt identisch ist.</summary>
        <returns>True, wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist. andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Key.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="key.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">Das Objekt, das mit dem aktuellen Objekt verglichen werden soll.</param>
        <summary>Bestimmt, ob das angegebene Objekt mit dem aktuellen Objekt identisch ist.</summary>
        <returns>True, wenn das angegebene Objekt mit dem aktuellen Objekt identisch ist. andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.TokenProvider.Key.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="key.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt den Hashcode für den Schlüssel zurück.</summary>
        <returns>Der Hashcode für den Schlüssel.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>